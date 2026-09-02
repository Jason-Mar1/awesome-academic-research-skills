# Awesome Academic Research Skills

[English](README.md) | [简体中文](README.zh-CN.md)

> A curated, workflow-first index of public agent skills, skill packs, research agents, and supporting tools for academic research.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Verification snapshot: 2026-09-02.** This is a discovery index, not an endorsement or a benchmark. Project descriptions, host labels, and licenses are concise upstream-facing metadata; always read the linked repository and its current terms before installing or reusing anything.

> **New through GitHub research.** Entries marked **New** were added after a GitHub-source review for this edition. Popularity metrics are deliberately omitted because they change quickly and are not quality evidence.

## How to use this list

Pick a workflow stage first, then use the discipline legend and host column to narrow candidates. Each repository has one primary home where practical, so a project is not repeated merely because it covers several stages.

### Discipline legend

| Code | Best fit |
| --- | --- |
| `X` | Cross-disciplinary |
| `CS/AI` | Computer science and artificial intelligence |
| `EP` | Engineering and physical sciences |
| `LS/M` | Life science and medicine |
| `C/M` | Chemistry and materials |
| `SS/E` | Social science and economics |
| `H/L` | Humanities and language |

### License labels

`Not detected†` means no obvious repository-level SPDX identifier or root license was detected in the review snapshot. `Per-skill†` and `Mixed terms†` mean that the repository does not offer one simple reusable license for every item. These labels are not legal advice—inspect upstream terms before use, redistribution, or commercial work.

## Curated starting points

| Start here when you need… | Suggested project | Why it is a useful first look |
| --- | --- | --- |
| Evidence-led paper planning and revision | [MAIR scientific-paper-writing-skills](https://github.com/MAIR-Lab-HUST/scientific-paper-writing-skills) **New** | A compact writing workflow with claim–evidence discipline. |
| Broad scientific tools and computing workflows | [K-Dense scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | A large cross-domain library spanning data, literature, and scientific tooling. |
| Reproducible research-to-paper checkpoints | [AI4S Skills](https://github.com/ai4s-research/ai4s-skills) **New** | Explicit research, experiment, writing, and integrity-oriented workflows. |
| Publication figures with QA steps | [Academic Figure Skill](https://github.com/TingxiYu/academic-figure-skill) **New** | Figure planning, multi-panel work, and quality checks in one focused skill. |
| Source-grounded citation work | [grounded-citations](https://github.com/NousResearch/hermes-agent/blob/main/skills/research/grounded-citations/SKILL.md) **New** | A narrow entry point for keeping claims tied to inspectable sources. |
| Life-science research support | [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills) **New** | Broad bioinformatics, clinical, visualization, and research-format coverage. |
| Chinese-first research workflow support | [Tashan Research Skills](https://github.com/TashanGKD/tashan-research-skills) **New** | Chinese academic writing, statistics, visualization, and presentation workflows. |

## End-to-end research workflows

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | Research-to-revision workflow with staged checkpoints. | `X` | Claude Code / skill-compatible hosts | CC BY-NC 4.0 |
| [academic-research-skills-codex](https://github.com/Imbad0202/academic-research-skills-codex/tree/main/skills/academic-research-suite) | Codex-oriented suite for literature, writing, review, and experiments. | `X` | Codex | CC BY-NC 4.0 |
| [claude-scholar](https://github.com/Galaxy-Dawn/claude-scholar/tree/codex) | Semi-automated research flow from ideas and code to papers and publication assets. | `CS/AI`, `X` | Codex CLI / Claude Code / Kimi / OpenCode | MIT |
| [AlterLab-Academic-Skills](https://github.com/AlterLab-IEU/AlterLab-Academic-Skills) | Multi-domain academic workflows with evaluation and citation checks. | `X` | Agent-skill hosts (see upstream) | MIT |
| [scientific-paper-writing-skills](https://github.com/MAIR-Lab-HUST/scientific-paper-writing-skills) **New** | Evidence-led planning, drafting, and revision for scientific papers. | `X`, `CS/AI` | Codex skill | CC BY 4.0 |
| [academic-skills](https://github.com/voidful/academic-skills) **New** | Modular academic research and writing tasks for agent workflows. | `X` | SKILL.md-compatible hosts | MIT |
| [ai4s-skills](https://github.com/ai4s-research/ai4s-skills/tree/main/skills/experiment-suite) **New** | Research planning, executable experiments, writing, and integrity checks. | `X`, `EP`, `LS/M` | Claude; documented Codex/Cursor/Aider paths | MIT |
| [Academic-Research-Agent-Skill](https://github.com/ngtiendong/Academic-Research-Agent-Skill/blob/main/SKILL.md) **New** | Evidence review, novelty framing, formalization, experiment design, and mock review. | `CS/AI`, `EP` | Claude / Codex-style / Gemini / local LLMs | MIT |

## Literature, reading, and evidence

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [PaperSpine](https://github.com/WUBING2023/PaperSpine) | Reconstructs motivation, argument, evidence, and revision logic from papers. | `X` | Markdown / agent-skill hosts | MIT |
| [paper-search-mcp](https://github.com/openags/paper-search-mcp) | MCP infrastructure for literature discovery and paper search. | `X` | MCP clients | MIT |
| [grounded-citations](https://github.com/NousResearch/hermes-agent/blob/main/skills/research/grounded-citations/SKILL.md) **New** | Supports source-grounded claims and citation-oriented research notes. | `X` | Hermes Agent / SKILL.md-compatible hosts | MIT |

## Research design, experiments, and scientific computing

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | Scientific databases, analysis, computing, and domain-tool workflows. | `LS/M`, `C/M`, `EP`, `X` | Codex / Claude / Cursor and related agents | MIT |
| [Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | Iterative ML ideas, experiments, and cross-model review loops. | `CS/AI` | Claude Code / research-agent scripts | MIT |
| [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | AI research engineering skills for model design, training, and optimization. | `CS/AI` | Coding-agent hosts (see upstream) | MIT |
| [Auto-Empirical-Research-Skills](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills) | Empirical research support for causal work, analysis, and statistics. | `SS/E`, `X` | Agent-skill hosts (see upstream) | Not detected† |
| [science-superpowers](https://github.com/K-Dense-AI/science-superpowers) **New** | Science-oriented agent capabilities and reusable research workflows. | `LS/M`, `C/M`, `EP` | Scientific-agent hosts (see upstream) | MIT |
| [scientific-problem-selection](https://github.com/anthropics/life-sciences/tree/main/scientific-problem-selection) **New** | Helps frame and select tractable life-science research problems. | `LS/M`, `C/M` | Anthropic Agent Skills | Upstream terms; no repo SPDX† |

## Academic writing and paper craft

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills) | Paper-writing workflows oriented to ML, CV, NLP, and technical research. | `CS/AI` | Agent-skill hosts (see upstream) | MIT |
| [academic-paper-skills](https://github.com/lishix520/academic-paper-skills) | Paper planning and composition with quality checkpoints. | `X` | Agent-skill hosts (see upstream) | MIT |
| [codex-claude-academic-skills](https://github.com/zLanqing/codex-claude-academic-skills) | Paper reading, writing, and research programming for coding agents. | `CS/AI`, `EP` | Codex / Claude | MIT |
| [nature-skills](https://github.com/Yuan1z0825/nature-skills) | Nature-style scientific expression and research-figure guidance. | `LS/M`, `C/M`, `EP` | Agent-skill hosts (see upstream) | Apache-2.0 |
| [writing-skills](https://github.com/msimchowitz/writing-skills) **New** | Structured drafting and revision support for clear, rigorous prose. | `X`, `H/L` | SKILL.md-compatible hosts | MIT |

## Figures and visualization

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [academic-figure-skill](https://github.com/TingxiYu/academic-figure-skill/blob/main/SKILL.md) **New** | Plans and quality-checks publication figures, multi-panels, and statistical graphics. | `X`, `LS/M` | Codex / Claude / Cursor / Copilot | Apache-2.0 |
| [research-grade-skills](https://github.com/Yuuqq/research-grade-skills/tree/main/scientific-skills/scientific-visualization) **New** | Auditable scientific visualization with related literature, poster, and slide support. | `X`, `CS/AI`, `EP` | Codex / Claude / Cursor | MIT |
| [tashan-research-skills](https://github.com/TashanGKD/tashan-research-skills/tree/main/skills/statistical-analysis) **New** | Chinese research statistics, figures, presentations, and paper checks. | `X`, `SS/E`, `CS/AI` | Codex (Windows) / Claude / Cursor | MIT |
| [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills/tree/main/skills/data-visualization/scientific-visualization) **New** | Life-science visualization, bioinformatics, clinical statistics, and research assets. | `LS/M`, `C/M` | Codex / Claude / Cursor / Windsurf | CC BY 4.0 |
| [scifig-ai-scientific-figure-skill](https://github.com/lilingm963/scifig-ai-scientific-figure-skill/tree/main/skills/scifig-scientific-figure) **New** | Concept figures, graphical abstracts, workflows, and research-roadmap diagrams. | `X`, `EP`, `LS/M` | Codex / Claude / OpenClaw / Hermes | MIT |

## Peer review, rebuttal, and research integrity

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [Supervisor-Skills](https://github.com/HKUSTDial/Supervisor-Skills) | Research mentoring, idea assessment, paper polishing, and pre-submission review. | `X`, `CS/AI` | Agent-skill hosts (see upstream) | Not detected† |
| [research-paper](https://github.com/aniketkrs/research-paper) **New** | Research-paper workflow support for drafting, critique, and submission preparation. | `X`, `CS/AI` | SKILL.md-compatible hosts | MIT |

## Style and voice support — supporting tools, not research-native evidence systems

These tools can improve a draft's clarity or voice, but they do **not** validate methods, data, novelty, citations, or factual claims. Preserve author responsibility and source checking.

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [academic-humanizer](https://github.com/AIScientists-Dev/academic-humanizer) | Post-draft academic style refinement and grant-writing voice support. | `X`, `H/L` | Agent-skill hosts (see upstream) | Not detected† |
| [humanizer](https://github.com/blader/humanizer) | Removes common AI-prose patterns from general writing. | `X`, `H/L` | Agent-skill hosts (see upstream) | MIT |
| [stop-slop](https://github.com/hardikpandya/stop-slop) | Post-draft English editing for filler, jargon, and repeated patterns. | `X`, `H/L` | Agent-skill hosts (see upstream) | MIT |
| [no-ai-slop](https://github.com/petergyang/no-ai-slop) | Revises recurring AI-writing patterns while aiming to preserve voice. | `X`, `H/L` | Agent-skill hosts (see upstream) | MIT |
| [shuorenhua](https://github.com/MrGeDiao/shuorenhua) | Chinese-first naturalization with fact-preservation emphasis. | `X`, `H/L` | Chinese writing-agent hosts | MIT |
| [qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei) | Simplified-Chinese revision for formulaic phrasing and flow. | `X`, `H/L` | Chinese writing-agent hosts | MIT |
| [De-AI-Prompt-Enhancer-Writer-Booster-SKILL](https://github.com/OUBIGFA/De-AI-Prompt-Enhancer-Writer-Booster-SKILL) | De-AI editing and style-reference-based writing assistance. | `X`, `H/L` | Agent-skill hosts (see upstream) | Not detected† |
| [writing-agent](https://github.com/dongbeixiaohuo/writing-agent) | Chinese writing workflow with drafting, reader testing, review, and formatting. | `X`, `H/L` | Claude Code | MIT |

## Delivery and research formats — supporting tools

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [Anthropic document skills (PDF / PPTX / XLSX)](https://github.com/anthropics/skills/tree/main/skills/pdf) **New** | Creates, reads, and quality-checks common research delivery formats; follow each skill's terms. | `X` | Claude Code / Claude API | Mixed terms† |

## Frameworks, registries, and domain catalogs — supporting/tool layer

These are discovery surfaces or broader frameworks rather than a single academic skill. Treat their internal skills as separate upstream artifacts with their own documentation and terms.

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [medical-research-skills](https://github.com/aipoch/medical-research-skills) | Domain collection for medical-research workflows. | `LS/M` | Agent-skill hosts (see upstream) | MIT |
| [deer-flow](https://github.com/bytedance/deer-flow) | General research-agent framework with literature-review capabilities. | `X`, `CS/AI` | DeerFlow framework / web stack | MIT |
| [academic-research-skills](https://github.com/franklee16/academic-research-skills) **New** | Economics, finance, social-science writing, analysis, visualization, and review skills. | `SS/E`, `X` | Claude Code | Per-skill†; root not detected |
| [OpenAI Skills](https://github.com/openai/skills) **New** | Official Codex skill catalog and examples for reusable agent capabilities. | `X` | Codex | Not detected† |

## Installation guidance

There is no safe universal installation command for this list. For each candidate:

1. Open the upstream repository and read its `README`, `SKILL.md`, installation steps, license, and any tool/API requirements.
2. Install only the specific skill or integration you need, following the upstream instructions for your host (for example, Codex, Claude Code, Cursor, or an MCP client).
3. Review scripts and requested permissions before granting filesystem, network, browser, credential, or cloud-data access.
4. Keep the upstream URL, version/commit, and license with any local copy so you can audit and update it later.

For Codex-style skills, upstream documentation normally specifies the target skill directory and any required configuration. Do not bulk-copy an entire catalog into a shared environment unless its terms, dependencies, and permissions have been reviewed.

## Security and research integrity

- Treat every third-party skill as executable instructions: inspect prompts, scripts, dependencies, and data flows before use.
- Do not expose unpublished manuscripts, reviewer comments, human-subject data, patient data, proprietary code, API keys, or institutional credentials to an unreviewed tool.
- Verify every citation, quotation, result, statistic, figure, and method against primary sources and your own records. A citation-oriented skill can assist retrieval; it cannot establish truth.
- Do not use a skill to fabricate evidence, hide limitations, evade venue rules, impersonate peer review, or misrepresent AI-assisted work. Follow journal, funder, institutional, and dataset policies.
- Keep human sign-off for scientific claims, experimental design, authorship, and submission decisions.

## Inclusion criteria

A listing should have a public repository and a reusable, documented workflow, skill, agent capability, tool integration, or research format utility. We favor projects that make scope, host compatibility, permissions, provenance, evaluation, and licensing clear.

We do not use star counts as quality scores, do not copy upstream skill text into this index, and do not list a generic prompt merely because it mentions research. Supporting tools are labeled as such rather than presented as evidence or peer-review systems.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull request. A useful submission includes the exact upstream URL, one factual sentence about the capability, its primary workflow category, discipline fit, supported hosts, and license status. Please avoid promotional wording and disclose unavailable or unclear licensing.

## License of this index

The index itself is released under [CC0-1.0](LICENSE). Every linked project remains subject to its own license, terms, and attribution requirements.
