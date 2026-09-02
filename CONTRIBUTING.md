# Contributing / 贡献指南

Thank you for helping keep this a practical, trustworthy, bilingual directory of academic agent skills.

This repository lists useful, inspectable tools. A listing is **not** an endorsement, a security guarantee, or evidence that a skill is suitable for a particular study, institution, or research claim.

## English

### What we accept

Submit a skill only when it has all of the following:

- A **public GitHub repository** with a stable URL.
- A concrete `SKILL.md`, or a clearly documented skill pack/integration that explains its commands, files, and expected host.
- One primary workflow category and a concise description of the research task it supports.
- Its discipline fit (for example, general academic research, computer science, biomedicine, social science, humanities, or interdisciplinary).
- Its supported host(s) or platform(s), such as Codex, Claude Code, Cursor, OpenAI API, a CLI, or a web application.
- A detectable license, or the explicit value `Not detected` after checking the repository.
- A maintenance signal: a recent release/commit, active issue responses, an owner-maintained roadmap, or another verifiable sign that the project is not abandoned.
- A runnable example, sample prompt, test, or documented expected output where feasible.

We welcome skills for writing, literature discovery, figures and visualization, data/experiments, reviewing, citations, submission checks, and related research workflows. Add **one primary category** using a README section; mention secondary uses in the description rather than duplicating the listing.

### What we do not accept

- Generic prompt dumps, untested role-play prompts, or a list of links with no concrete integration.
- Private, inaccessible, paywalled-only, or unverifiable repositories.
- Marketing claims presented as academic evidence, including invented accuracy, benchmark, citation, publication, or affiliation claims.
- Tools that conceal risky behavior, such as credential harvesting, undisclosed network calls, or destructive file/git/database operations.

### Before opening a pull request

1. Check for an existing entry and propose an update instead of a duplicate.
2. Inspect the repository and its documentation; do not rely on its README alone for licensing or behavior claims.
3. Review scripts, install commands, network access, and operations that can overwrite, delete, publish, or transmit data. Summarize any material risks.
4. Use the exact row format below in the appropriate README category table:

   ```markdown
   | Name | What it does | Discipline fit | Hosts | License |
   | --- | --- | --- | --- | --- |
   | [example-skill](https://github.com/example/example-skill) | Evidence-led manuscript planning and revision | General academic research; CS | Codex | MIT |
   ```

5. Under the row, or in the PR body when the table should stay compact, include:

   - **Evidence/examples:** a demo, test, sample workflow, or documented output.
   - **Maintenance signal:** a dated release/commit or other verifiable activity.
   - **External dependencies:** required host, API, model, service, credentials, or paid component.
   - **Security notes:** scripts inspected; network/data transfer; destructive or publishing behavior; unresolved concerns.

6. Keep descriptions factual, short, and sourceable. Do not imply that a listed skill replaces expert judgment, ethical review, reproducibility work, or venue requirements.

### Review process

Maintainers may edit wording, move the entry to a better category, request evidence, or decline an entry that cannot be verified. We prioritize transparent projects with clear scope and safe operational behavior.

## 简体中文

感谢你帮助维护这个实用、可信、支持中英双语的学术 Agent Skill 目录。

本仓库只收录可检查、可追溯的工具。被收录 **不代表** 本仓库对其背书，不构成安全保证，也不表示该 Skill 适用于任何特定研究、机构或学术结论。

### 收录要求

提交的 Skill 应同时满足以下要求：

- 有可公开访问、链接稳定的 **GitHub 仓库**。
- 提供明确的 `SKILL.md`，或提供文档完整的 Skill 包/集成方式，说明命令、文件和预期运行宿主。
- 说明一个主要工作流分类，以及它支持的具体研究任务。
- 标明适配学科，例如通用学术研究、计算机科学、生物医学、社会科学、人文或交叉学科。
- 标明支持的宿主/平台，例如 Codex、Claude Code、Cursor、OpenAI API、CLI 或 Web 应用。
- 有可识别的许可证；若已核查但未找到，必须明确写为 `Not detected`。
- 提供维护信号：近期 release/commit、活跃 issue 回复、维护路线图，或其他可核验的持续维护证据。
- 在可行时提供可运行示例、示例提示词、测试，或有文档说明的预期输出。

欢迎收录论文写作、文献发现、科研绘图与可视化、数据与实验、审稿、引文与投稿检查等研究工作流 Skill。每个条目只从 README 的章节中指定 **一个主要分类**；其他用途请写在描述中，不要重复收录。

### 不收录的内容

- 泛化提示词堆砌、未经验证的角色扮演提示词，或没有明确集成方式的链接集合。
- 私有、无法访问、仅付费墙内可用，或无法核验的仓库。
- 将营销话术当作学术证据的内容，包括虚构的准确率、基准、引用、发表记录或机构关联。
- 隐藏风险行为的工具，例如凭据收集、未披露的网络访问，或可破坏文件/Git/数据库的操作。

### 提交 Pull Request 前

1. 先检查是否已有相同条目；若已有，请提交更新而非重复条目。
2. 检查仓库及其文档；不要只依据 README 判断许可证或行为。
3. 审查脚本、安装命令、网络访问，以及可能覆盖、删除、发布或传输数据的操作，并概述重要风险。
4. 在相应 README 分类表中使用以下完全一致的行格式：

   ```markdown
   | Name | What it does | Discipline fit | Hosts | License |
   | --- | --- | --- | --- | --- |
   | [example-skill](https://github.com/example/example-skill) | Evidence-led manuscript planning and revision | General academic research; CS | Codex | MIT |
   ```

5. 在条目下方，或为保持表格简洁而在 PR 描述中补充：

   - **Evidence/examples：** 演示、测试、样例工作流，或有文档说明的输出。
   - **Maintenance signal：** 带日期的 release/commit，或其他可验证的活跃维护迹象。
   - **External dependencies：** 所需宿主、API、模型、服务、凭据或付费组件。
   - **Security notes：** 已检查的脚本；网络/数据传输；破坏性或发布性操作；仍未解决的风险。

6. 描述应简短、客观且可溯源。不要暗示任何条目可以替代专家判断、伦理审查、可复现性工作或投稿要求。

### 审核方式

维护者可以修改表述、调整分类、要求补充证据，或拒绝无法核验的条目。我们优先收录范围清晰、信息透明且运行行为安全的项目。
