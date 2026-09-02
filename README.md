# Awesome Academic Research Skills

[English](README.md) | [简体中文](README.zh-CN.md)

> A curated, workflow-first index of public agent skills, skill packs, research agents, and supporting tools for academic research.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Verification snapshot: 2026-09-02.** This is a discovery index, not an endorsement or a benchmark. Project descriptions, host labels, and licenses are concise upstream-facing metadata; always read the linked repository and its current terms before installing or reusing anything.

> **Expanded in this edition.** It adds 26 verified entries (11 community-suggested + 15 independent GitHub finds). Popularity metrics are omitted because they drift and do not prove quality.

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
| `Geo/Env` | Earth and environmental sciences |
| `SS/E` | Social science and economics |
| `H/L` | Humanities and language |

### License labels

`Not detected†` means no obvious repository-level SPDX identifier or root license was detected in the review snapshot. `Per-skill†` and `Mixed terms†` mean that the repository does not offer one simple reusable license for every item. `Academic-use-only†` and custom non-commercial labels are restrictive upstream terms, not standard open-source licenses. These labels are not legal advice—inspect upstream terms before use, redistribution, or commercial work.

## Curated starting points

| Start here when you need… | Suggested project | Why it is a useful first look |
| --- | --- | --- |
| Evidence-led paper planning and revision | [MAIR scientific-paper-writing-skills](https://github.com/MAIR-Lab-HUST/scientific-paper-writing-skills) | A compact writing workflow with claim–evidence discipline. |
| Broad scientific tools and computing workflows | [K-Dense scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | A large cross-domain library spanning data, literature, and scientific tooling. |
| Reproducible research-to-paper checkpoints | [AI4S Skills](https://github.com/ai4s-research/ai4s-skills) | Explicit research, experiment, writing, and integrity-oriented workflows. |
| Publication figures with QA steps | [Academic Figure Skill](https://github.com/TingxiYu/academic-figure-skill) | Figure planning, multi-panel work, and quality checks in one focused skill. |
| Source-grounded citation work | [grounded-citations](https://github.com/NousResearch/hermes-agent/blob/main/skills/research/grounded-citations/SKILL.md) | A narrow entry point for keeping claims tied to inspectable sources. |
| Life-science research support | [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills) | Broad bioinformatics, clinical, visualization, and research-format coverage. |
| Chinese-first research workflow support | [Tashan Research Skills](https://github.com/TashanGKD/tashan-research-skills) | Chinese academic writing, statistics, visualization, and presentation workflows. |
| CCF-A research lifecycle in CS/AI | [CCFA-Skills](https://github.com/mikubaka88/CCFA-Skills) | Seventeen skills covering idea, literature, experiments, writing, review, rebuttal, and submission. |
| Venue-focused rebuttal work | [Rebuttal-Skill](https://github.com/TobiasLee/Rebuttal-Skill/blob/main/SKILL.md) | Reviewer triage, experiment prioritization, and response QA; its license is not detected and confidentiality still needs review. |
| Science data and tool workflows | [Google DeepMind science-skills](https://github.com/google-deepmind/science-skills) | Domain skills for scientific data, databases, and tooling; upstream code, content, skills, and data use mixed terms. |
| Economics and econometrics | [EconAgentSkills](https://github.com/JonasWeinert/EconAgentSkills) | DiD, IV, RDD, analysis, tables, and visualization across R, Stata, and Python. |
| Materials simulation and reproducibility | [materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills) | Numerical stability, DOE, HPC, V&V, and FAIR practices for computational materials. |

## End-to-end research workflows

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | Research-to-revision workflow with staged checkpoints. | `X` | Claude Code / skill-compatible hosts | CC BY-NC 4.0 |
| [academic-research-skills-codex](https://github.com/Imbad0202/academic-research-skills-codex/tree/main/skills/academic-research-suite) | Codex-oriented suite for literature, writing, review, and experiments. | `X` | Codex | CC BY-NC 4.0 |
| [claude-scholar](https://github.com/Galaxy-Dawn/claude-scholar/tree/codex) | Semi-automated research flow from ideas and code to papers and publication assets. | `CS/AI`, `X` | Codex CLI / Claude Code / Kimi / OpenCode | MIT |
| [AlterLab-Academic-Skills](https://github.com/AlterLab-IEU/AlterLab-Academic-Skills) | Multi-domain academic workflows with evaluation and citation checks. | `X` | Agent-skill hosts (see upstream) | MIT |
| [scientific-paper-writing-skills](https://github.com/MAIR-Lab-HUST/scientific-paper-writing-skills) | Evidence-led planning, drafting, and revision for scientific papers. | `X`, `CS/AI` | Codex skill | CC BY 4.0 |
| [academic-skills](https://github.com/voidful/academic-skills) | Modular academic research and writing tasks for agent workflows. | `X` | SKILL.md-compatible hosts | MIT |
| [ai4s-skills](https://github.com/ai4s-research/ai4s-skills/tree/main/skills/experiment-suite) | Research planning, executable experiments, writing, and integrity checks. | `X`, `EP`, `LS/M` | Claude; documented Codex/Cursor/Aider paths | MIT |
| [Academic-Research-Agent-Skill](https://github.com/ngtiendong/Academic-Research-Agent-Skill/blob/main/SKILL.md) | Evidence review, novelty framing, formalization, experiment design, and mock review. | `CS/AI`, `EP` | Claude / Codex-style / Gemini / local LLMs | MIT |
| [CCFA-Skills](https://github.com/mikubaka88/CCFA-Skills) | Seventeen-skill CCF-A lifecycle for AI/CS research. | `CS/AI` | Codex / Claude / Cursor / Gemini | MIT |
| [open-scholar-skill](https://github.com/joshzyj/open-scholar-skill) | Social-science lifecycle with causal and qualitative analysis, ethics, and monitoring. | `SS/E`, `H/L` | Claude-first; manual Codex loading | Custom academic/educational non-commercial license† |
| [research-paper-lifecycle-skills](https://github.com/ShaishavMaisuria/research-paper-lifecycle-skills) | Literature-to-submission, rebuttal, and camera-ready workflow; network services may require `CONTACT_EMAIL`. | `X` | Codex / Claude / Cursor / Gemini / Agent Skills hosts | Apache-2.0 |

## Literature, reading, and evidence

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [PaperSpine](https://github.com/WUBING2023/PaperSpine) | Reconstructs motivation, argument, evidence, and revision logic from papers. | `X` | Markdown / agent-skill hosts | MIT |
| [paper-search-mcp](https://github.com/openags/paper-search-mcp) | MCP infrastructure for literature discovery and paper search. | `X` | MCP clients | MIT |
| [grounded-citations](https://github.com/NousResearch/hermes-agent/blob/main/skills/research/grounded-citations/SKILL.md) | Supports source-grounded claims and citation-oriented research notes. | `X` | Hermes Agent / SKILL.md-compatible hosts | MIT |
| [Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills/blob/master/skills/research-codex-en/research/SKILL.md) | Outline-to-investigation-to-report workflow; web-research configuration or Exa may be needed. | `X` | Codex / Claude / OpenCode | MIT |
| [zotero-skills](https://github.com/WenyuChiou/zotero-skills/blob/master/skills/zotero-skills/SKILL.md) | Read/write Zotero-library management; API credentials and bulk actions require careful review. | `X` | Codex / Claude / Gemini / Cursor | MIT |
| [slr-prisma](https://github.com/keemanxp/slr-prisma) | PRISMA 2020 systematic-review workflow and documents; it does not perform meta-analysis. | `X` | Claude-first; manual portability | MIT; PRISMA assets CC BY 4.0 |

## Research design, experiments, and scientific computing

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | Scientific databases, analysis, computing, and domain-tool workflows. | `LS/M`, `C/M`, `EP`, `X` | Codex / Claude / Cursor and related agents | MIT |
| [Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | Iterative ML ideas, experiments, and cross-model review loops. | `CS/AI` | Claude Code / research-agent scripts | MIT |
| [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | AI research engineering skills for model design, training, and optimization. | `CS/AI` | Coding-agent hosts (see upstream) | MIT |
| [Auto-Empirical-Research-Skills](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills) | Empirical research support for causal work, analysis, and statistics. | `SS/E`, `X` | Agent-skill hosts (see upstream) | Not detected† |
| [science-superpowers](https://github.com/K-Dense-AI/science-superpowers) | Science-oriented agent capabilities and reusable research workflows. | `LS/M`, `C/M`, `EP` | Scientific-agent hosts (see upstream) | MIT |
| [scientific-problem-selection](https://github.com/anthropics/life-sciences/tree/main/scientific-problem-selection) | Helps frame and select tractable life-science research problems. | `LS/M`, `C/M` | Anthropic Agent Skills | Upstream terms; no repo SPDX† |
| [Google DeepMind science-skills](https://github.com/google-deepmind/science-skills) | Databases, genomics, structural biology, cheminformatics, and literature workflows. | `LS/M`, `C/M`, `EP` | Agent Skills hosts / Antigravity | Mixed terms† (code Apache-2.0; non-code CC BY 4.0; per-skill/data terms) |
| [phd-skills](https://github.com/fcakyon/phd-skills/blob/main/plugin/skills/reproduce/SKILL.md) | ML reproduction, experiment launch/debug/compare, and paper-code audit; can launch long or remote jobs. | `CS/AI` | Claude Code plugin | MIT |
| [materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills) | Computational materials: numerical stability, DOE, HPC, V&V, and FAIR practice. | `C/M`, `EP` | Codex / Claude / Cursor / Copilot | Apache-2.0 |
| [EconAgentSkills](https://github.com/JonasWeinert/EconAgentSkills) | Economics/econometrics workflows for DiD, IV, RDD, R/Stata/Python, tables, and visualization. | `SS/E` | Codex / Claude / Cursor / Gemini | CC0-1.0 |
| [Deep-Matter-Chem-Skills](https://github.com/SFETNI/Deep-Matter-Chem-Skills) | Draft/research workflows for DFT, MD, MLIP, CALPHAD, and LCA; not independently expert-validated. | `C/M`, `EP` | Codex / Claude / manual loading | MIT |
| [bioresearch-agent](https://github.com/Alim430/bioresearch-agent) | Biomedical literature, DEG, enrichment, GWAS, and MR workflows; research-only, not clinical decision support. | `LS/M` | Codex / Claude / Cursor / generic agents | MIT |

## Academic writing and paper craft

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills) | Paper-writing workflows oriented to ML, CV, NLP, and technical research. | `CS/AI` | Agent-skill hosts (see upstream) | MIT |
| [academic-paper-skills](https://github.com/lishix520/academic-paper-skills) | Paper planning and composition with quality checkpoints. | `X` | Agent-skill hosts (see upstream) | MIT |
| [codex-claude-academic-skills](https://github.com/zLanqing/codex-claude-academic-skills) | Paper reading, writing, and research programming for coding agents. | `CS/AI`, `EP` | Codex / Claude | MIT |
| [nature-skills](https://github.com/Yuan1z0825/nature-skills) | Nature-style scientific expression and research-figure guidance. | `LS/M`, `C/M`, `EP` | Agent-skill hosts (see upstream) | Apache-2.0 |
| [writing-skills](https://github.com/msimchowitz/writing-skills) | Structured drafting and revision support for clear, rigorous prose. | `X`, `H/L` | SKILL.md-compatible hosts | MIT |
| [Nature-Paper-Skills](https://github.com/Boom5426/Nature-Paper-Skills/blob/main/skills/core/paper-workflow/SKILL.md) | Nature/journal-first drafting, claim–figure alignment, audit, submission, and response. | `X` | Codex / Claude | Mixed terms† (own MIT; vendored Apache-2.0) |
| [academic-writing-skills](https://github.com/bahayonghang/academic-writing-skills/blob/main/academic-writing-skills/paper-audit/SKILL.md) | Paper/thesis audit for LaTeX, Typst, and references. | `X` | Codex / Claude | Academic-use-only, non-commercial† |
| [paper-writing-skill](https://github.com/SNL-UCSB/paper-writing-skill/blob/main/SKILL.md) | Brainstorming to architecture, draft, and compression for systems, networking, and ML; adapt lab-specific style. | `CS/AI`, `EP` | Claude Code | MIT |
| [academic-writing-skills](https://github.com/WenyuChiou/academic-writing-skills/blob/main/skills/academic-writing-skills/SKILL.md) | Evidence-driven framing, outline, drafting, revision, and verification. | `X` | Codex / Claude / OpenCode / Hermes | MIT |
| [manuscript-writing](https://github.com/YSLAB-ai/manuscript-writing/blob/main/SKILL.md) | Lightweight manuscript revision/review with evidence boundaries; no explicit test/evaluation signal. | `X` | Codex / Claude / OpenClaw / general hosts | MIT |

## Figures and visualization

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [academic-figure-skill](https://github.com/TingxiYu/academic-figure-skill/blob/main/SKILL.md) | Plans and quality-checks publication figures, multi-panels, and statistical graphics. | `X`, `LS/M` | Codex / Claude / Cursor / Copilot | Apache-2.0 |
| [research-grade-skills](https://github.com/Yuuqq/research-grade-skills/tree/main/scientific-skills/scientific-visualization) | Auditable scientific visualization with related literature, poster, and slide support. | `X`, `CS/AI`, `EP` | Codex / Claude / Cursor | MIT |
| [tashan-research-skills](https://github.com/TashanGKD/tashan-research-skills/tree/main/skills/statistical-analysis) | Chinese research statistics, figures, presentations, and paper checks. | `X`, `SS/E`, `CS/AI` | Codex (Windows) / Claude / Cursor | MIT |
| [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills/tree/main/skills/data-visualization/scientific-visualization) | Life-science visualization, bioinformatics, clinical statistics, and research assets. | `LS/M`, `C/M` | Codex / Claude / Cursor / Windsurf | CC BY 4.0 |
| [scifig-ai-scientific-figure-skill](https://github.com/lilingm963/scifig-ai-scientific-figure-skill/tree/main/skills/scifig-scientific-figure) | Concept figures, graphical abstracts, workflows, and research-roadmap diagrams. | `X`, `EP`, `LS/M` | Codex / Claude / OpenClaw / Hermes | MIT |

## Peer review, rebuttal, and research integrity

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [Supervisor-Skills](https://github.com/HKUSTDial/Supervisor-Skills) | Research mentoring, idea assessment, paper polishing, and pre-submission review. | `X`, `CS/AI` | Agent-skill hosts (see upstream) | Not detected† |
| [research-paper](https://github.com/aniketkrs/research-paper) | Research-paper workflow support for drafting, critique, and submission preparation. | `X`, `CS/AI` | SKILL.md-compatible hosts | MIT |
| [Rebuttal-Skill](https://github.com/TobiasLee/Rebuttal-Skill/blob/main/SKILL.md) | Reviewer triage, experiment prioritization, and response QA for NeurIPS, ICML, ACL, and CVPR; follow venue policy, human control, and confidentiality. | `CS/AI` | Claude / OpenCode / Gemini | Not detected† |
| [research-skills](https://github.com/neuromechanist/research-skills/blob/main/plugins/manuscript/skills/paper-review/SKILL.md) | Fresh-context paper review with citation, format, and figure QA; a full panel needs an agent template. | `X` | Codex / Claude / Copilot | BSD-3-Clause |
| [nature-reviewer-skills](https://github.com/GeoGeekLab/nature-reviewer-skills) | Domain review for earth/environment, chemistry, engineering, and materials; includes tests/benchmarks. | `Geo/Env`, `C/M`, `EP` | Manual SKILL.md loading / Codex | MIT |

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
| [sciwrite](https://github.com/labarba/sciwrite/blob/main/SKILL.md) | Scientific clarity, style, and consistency audit; it does not verify external citations. | `X`, `H/L` | Claude / ChatGPT / Gemini / general prompt hosts | CC BY 4.0 |

## Delivery and research formats — supporting tools

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [Anthropic document skills (PDF / PPTX / XLSX)](https://github.com/anthropics/skills/tree/main/skills/pdf) | Creates, reads, and quality-checks common research delivery formats; follow each skill's terms. | `X` | Claude Code / Claude API | Mixed terms† |
| [project20XXy](https://github.com/quarcs-lab/project20XXy) | Reproducible empirical template for Quarto, Python, R, and Stata; supports PDF, HTML, DOCX, LaTeX, and Overleaf. | `SS/E`, `X` | Claude Code-first | MIT |

## Frameworks, registries, and domain catalogs — supporting/tool layer

These are discovery surfaces or broader frameworks rather than a single academic skill. Treat their internal skills as separate upstream artifacts with their own documentation and terms.

| Name | What it does | Discipline fit | Hosts | License |
| --- | --- | --- | --- | --- |
| [medical-research-skills](https://github.com/aipoch/medical-research-skills) | Domain collection for medical-research workflows. | `LS/M` | Agent-skill hosts (see upstream) | MIT |
| [deer-flow](https://github.com/bytedance/deer-flow) | General research-agent framework with literature-review capabilities. | `X`, `CS/AI` | DeerFlow framework / web stack | MIT |
| [academic-research-skills](https://github.com/franklee16/academic-research-skills) | Economics, finance, social-science writing, analysis, visualization, and review skills. | `SS/E`, `X` | Claude Code | Per-skill†; root not detected |
| [OpenAI Skills](https://github.com/openai/skills) | Official Codex skill catalog and examples for reusable agent capabilities. | `X` | Codex | Not detected† |
| [FAROS](https://github.com/OpenNSWM-Lab/FAROS) | Full-stack LLM AutoResearch runtime, not a portable `SKILL.md` pack; code execution and credentials need review. | `CS/AI`, `X` | Python / Node / Docker / LaTeX / model provider | Not detected† |
| [AcademicForge](https://github.com/HughYau/AcademicForge) | Multi-pack registry and installer; upstream packs keep their own terms. | `X` | Codex / Claude / OpenCode | Mixed terms† (MIT core; upstream packs retain their licenses) |
| [research-hub](https://github.com/WenyuChiou/research-hub) | Persistent literature workspace/runtime with 12 skills and Zotero, Obsidian, and NotebookLM links; it may write external data or use OAuth. | `X` | Codex / Claude / Cursor / Gemini + MCP/REST | MIT |
| [MatClaw](https://github.com/DingyangLyu/MatClaw) | Advanced materials runtime with many `SKILL.md` files and a custom environment; not a lightweight one-command Codex skill. | `C/M`, `EP` | MatClaw / Docker / HPC | Apache-2.0 |

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
- Give automatic runtimes, library-writing tools, and confidential-review workflows extra permission and data review before connecting accounts, making bulk changes, or handling restricted material.
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
