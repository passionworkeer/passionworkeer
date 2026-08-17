<div align="center">

# Jianjun Wang

**AI-native Product Manager · Agent Engineer · Data Science @ Shenzhen Technology University**

I turn ambiguous business problems into AI systems that can reason, act, verify, and improve.

[![GitHub](https://img.shields.io/badge/GitHub-passionworkeer-181717?style=flat&logo=github)](https://github.com/passionworkeer)
[![Email](https://img.shields.io/badge/Email-17820577270@163.com-EA4335?style=flat&logo=gmail)](mailto:17820577270@163.com)
[![Location](https://img.shields.io/badge/Location-Shenzhen-1677FF?style=flat&logo=googlemaps&logoColor=white)](https://github.com/passionworkeer)
[![Visitors](https://komarev.com/ghpvc/?username=passionworkeer&color=brightgreen&style=flat&label=Profile+Views)](https://github.com/passionworkeer)

</div>

---

## About Me

I work at the intersection of **product judgment, Agent systems, and engineering execution**.

- AI Product Manager Intern at Banana in, working on enterprise AI, intelligent customer service, workflow automation, knowledge systems, and visual AIGC
- Able to move from business discovery to PRDs, domain models, data taxonomies, Agent/RAG workflows, evaluation systems, and working prototypes
- Interested in **AI-native products, Agent engineering, FDE-style delivery, multi-agent reliability, and long-term memory**
- Studying Data Science and Big Data Technology at Shenzhen Technology University

My usual working loop is:

**Problem discovery → workflow redesign → system modeling → Agent implementation → evaluation → iteration**

---

## Current Focus

### Reliable Agent Systems

> Studying factual belief disagreement between agents as an early-warning signal for silent failures in shared-memory multi-agent systems.

Current topics include:

- shared-memory consistency and false-success detection
- online cross-agent belief-divergence measurement
- lightweight pre-action audits and environment-oracle validation
- adaptations of τ-bench / τ²-bench for memory reliability research

### Enterprise AI Productization

Turning real workflows into AI systems with clear boundaries and measurable outcomes:

- requirement discovery and workflow redesign
- intent taxonomy, evaluation sets, and quality assurance
- RAG / Agent architecture and tool integration
- human-in-the-loop routing, exception handling, and fallback design
- dashboards, delivery validation, and continuous iteration

Some current competition and enterprise projects remain private, so this profile only links work that is suitable for public review.

---

## Featured Projects

### [yt · Shared Memory Bus](https://github.com/passionworkeer/obsidian-shared-memory-bus)

A local-first shared-memory runtime that lets Claude Code, Codex, Cursor, Claude Desktop, and other MCP clients share structured memory.

- MCP-based cross-tool retrieval, writing, and memory management
- local JSONL event storage, search indexes, and derived Markdown documents
- BM25 and local hash-embedding retrieval with optional remote embedding backends
- split services, cross-platform runtime support, CI, security hardening, and operational tooling

`Node.js` `Python` `MCP` `SQLite` `BM25` `RAG` `Local-first AI`

### Code Knowledge Base & Agent Governance — Tencent × SZDT joint program `private repo`

An evaluation and governance suite for cross-file dependency analysis on real repositories, comparing prompt engineering, retrieval, and domain adaptation.

- manually reviewed 54-case evaluation set with strict scoring audits
- systematic comparison of baseline, PE, RAG, LoRA, and combined strategies
- AST-aware retrieval, bad-case diagnosis, ablation studies, and reproducible reports
- trace-driven MCP tool governance: cross-file analysis F1 0.28 → 0.61

`Python` `AST` `RAG` `LoRA` `MCP` `LLM Evaluation` `Tree-sitter`

> Repo kept private per collaboration terms. Live write-up: [resume.wangjianjun.xyz](https://resume.wangjianjun.xyz) → Work → RepoMind.

### [TwinBuddy / 拼途旅行](https://github.com/passionworkeer/twinbuddy) — 🏆 2026 Douyin AI Hackathon 2nd Prize (Team Lead)

An AI-native companion-matching prototype where digital twins negotiate on behalf of users before presenting a match.

- 🏆 **2nd Prize, Track 3 — Douyin AI Innovator Program 2026 Hackathon League** (Team Lead of 4)
- MING persona distillation framework — ≥90% fidelity soul fingerprints from chat history
- bilateral Agent negotiation with LangGraph; 20s → 1.2s latency via Mega-Prompt single-call
- multi-dimensional compatibility scoring, SSE streaming, explainable match reports

`React` `TypeScript` `FastAPI` `LangGraph` `Multi-Agent`

### [longcode](https://github.com/passionworkeer/longcode)

A Claude Code skill prototype for turning a high-level requirement into a structured development workflow.

- requirement collection and task decomposition
- Agent-based implementation, review, testing, and retry loops
- atomic Git commits and resumable execution state
- reusable plans, reports, and quality gates for long-running coding tasks

`Claude Code` `Agent Harness` `Git Workflow` `Testing` `Prompt Engineering`

---

## Project Map

| Direction | Public Projects | What I explored |
|---|---|---|
| Agent Infrastructure & Memory | [yt](https://github.com/passionworkeer/obsidian-shared-memory-bus) | Shared memory, MCP, retrieval, runtime reliability, security |
| Evaluation & Research | private (Tencent × SZDT joint program) | PE / RAG / LoRA experiments, strict evaluation, bad-case analysis |
| AI-native Products | [TwinBuddy](https://github.com/passionworkeer/twinbuddy), [TRIX](https://github.com/passionworkeer/TRIX_ap), [CareerGuide](https://github.com/passionworkeer/career-guide) | Digital twins, AI companions, recommendation and decision products |
| Agent Tools & Prototypes | [longcode](https://github.com/passionworkeer/longcode), [Travel Agent](https://github.com/passionworkeer/gaode_agent), [AI Video Editor](https://github.com/passionworkeer/aivideochatcut) | Agent harnesses, MCP tools, multimodal workflows, browser and media automation |

---

## Contribution Trail

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake.svg" />
  <img alt="Animated contribution graph" src="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake.svg" />
</picture>

<sub>Generated daily from my public GitHub contribution graph.</sub>

</div>

---

## Experience

### AI Product Manager Intern · Banana in `2026.05 – present`

Working on the productization of AI across customer service, enterprise workflows, knowledge systems, and creative production.

- Translate business pain points into product requirements, system workflows, and measurable evaluation plans
- Design intent taxonomies, mapping rules, quality checks, dashboards, and human-handoff strategies for intelligent customer service
- Explore enterprise Agent platforms, workflow orchestration, browser automation, and internal knowledge applications
- Research visual AIGC workflows involving Photoshop plugins, ComfyUI, LoRA, and brand-consistency control
- Coordinate product, engineering, operations, and external vendors through testing and delivery

### AI Application Engineer · Shenzhen Linyuan Technology `2025.10 – 2025.12`

Built a multimodal AI content-generation system for cross-border e-commerce visual workflows.

- Designed an asynchronous architecture with FastAPI, Redis task queues, WebSocket delivery, and failure recovery
- Built a model-routing gateway for heterogeneous LLM and image-generation providers
- Constructed an LLM-as-a-Judge evaluation workflow and optimized prompts with few-shot examples

---

## Recognition

| Award | Role | Year |
|---|---|---:|
| [2nd Xinghan Cup National Legal AI Innovation Challenge](https://www.aiinnovation.hezher.com) — **National Top-8 Finalist** (final: Sep 2026, Shanghai) | Tech Lead | 2026 |
| [2026 Feishu AI Future Talent Cup](https://activity.feishu.cn/future-talent) — **National Top-100** (Top-40 review in progress) | Team Lead | 2026 |
| [Douyin AI Innovator Program 2026 Hackathon League](https://aiia.douyin.com/) — **2nd Prize, Track 3** | Team Lead | 2026 |
| [CUMCM National Math Modeling Contest](https://www.mcm.edu.cn/) — **Provincial 1st Prize (Guangdong)**, 68,311 teams | Team Lead | 2025 |
| 6th Huashu Cup National Math Modeling Contest — **National 1st Prize** | Team Lead | 2025 |
| 15th Zhengda Cup National Market Survey & Analysis Contest — **Provincial 1st Prize (Guangdong)**, 282k students | Team Member | 2025 |

<sub>Award names verified against official contest sites on 2026-08-17. 中文全名:第二届星瀚杯"全国大学生法律AI应用"创新挑战赛 全国八强 · 2026 AI 先锋未来人才大赛 全国百强 · 抖音 AI 创变者计划 2026 黑客松联赛 赛道三二等奖 · 2025 高教社杯全国大学生数学建模竞赛 广东省一等奖 · 第六届"华数杯"全国大学生数学建模竞赛 全国一等奖 · "正大杯"第十五届全国大学生市场调查与分析大赛 广东省一等奖</sub>

---

## Toolbox

**Product & Delivery**

`Product Discovery` `PRD` `Workflow Design` `Domain Modeling` `Intent Taxonomy` `Data Analysis` `Dashboard Design`

**Agents, Evaluation & Reliability**

`LangGraph` `LangChain` `Multi-Agent` `MCP` `RAG` `Shared Memory` `LLM Evaluation` `Prompt Engineering` `LoRA`

**Engineering**

<div align="center">

[![Skills](https://skillicons.dev/icons?i=python,fastapi,nodejs,react,ts,postgres,redis,docker,git,linux)](https://skillicons.dev)

</div>

---

<div align="center">

**Looking for opportunities where product judgment and engineering execution are equally important.**

AI Product · Agent Engineer · Applied AI · FDE

</div>
