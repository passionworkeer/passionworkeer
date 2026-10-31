<div align="center">

# 王健俊 · Wang Jianjun

**AI Agent Engineer · Evaluation · Backend Systems**

Backend Development Intern @ **Tencent** · Data Science @ **Shenzhen Technology University**

I build agents that use tools, produce verifiable results, and fit into real workflows.

[Portfolio](https://wangjianjun.xyz) · [Open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Apassionworkeer+-user%3Apassionworkeer) · [Projects](https://github.com/passionworkeer?tab=repositories)

<img src="assets/logos/tencent.svg" alt="Tencent 腾讯" width="115" /> &nbsp;&nbsp;
<img src="assets/logos/kuaishou.svg" alt="Kuaishou 快手" width="115" /> &nbsp;&nbsp;
<img src="assets/logos/bananain.svg" alt="Bananain 蕉内" width="115" />

<sub>Current: Tencent · Previously: Kuaishou &amp; Bananain</sub>
</div>

## Recent open-source contributions

<img src="assets/logos/opendal.svg" alt="Apache OpenDAL" width="112" align="left" />

**[Apache OpenDAL #8429 — avoid initializing unused writers on abort](https://github.com/apache/opendal/pull/8429)**<br/>
**Merged on October 30, 2026** · Rust · [apache/opendal](https://github.com/apache/opendal)

Aborting a lazy Fs writer no longer initializes its inner writer, so cancelling before the first write can no longer truncate an existing file or create the target and its parents. Added seven regression tests against real temporary filesystems; the official filesystem behavior suite (130 tests) passes with and without `atomic_write_dir`.

<br clear="left" />

<img src="assets/logos/nushell.png" alt="Nushell" width="32" align="left" />

**[Nushell #19348 — traverse explicit relative paths](https://github.com/nushell/nushell/pull/19348)**<br/>
**Merged on October 29, 2026** · Rust · [nushell/nushell](https://github.com/nushell/nushell)

Fixed explicit relative paths in the experimental `dc-glob` backend: patterns such as `./*.txt`, `../*.txt`, and `../**` now search the intended directory, and `.` / `..` return their matching directory.

<br clear="left" />

<sub>Also merged recently: [MCP Rust SDK #1382](https://github.com/modelcontextprotocol/rust-sdk/pull/1382) — Streamable HTTP matches explicit media types and honors `Accept` quality values (Oct 30) · [Nushell #19309](https://github.com/nushell/nushell/pull/19309) — `dc-glob` honors negated character classes (Oct 25).</sub>

## Experience

| When | Role | Focus |
| --- | --- | --- |
| **Oct 2026–present** | **Tencent 腾讯 · Backend Development Intern** | Monitoring data services: ingestion, analytical queries, usage metering, and data consistency. |
| Aug–Oct 2026 | **Kuaishou 快手 · Agent Development Intern** | Design-agent evaluation, structured Figma editing, MCP integration, and failure diagnosis. |
| Mar–Jul 2026 | **Bananain 蕉内 · AI Application Engineer** | AIGC visual workflows, design plugins, and enterprise agent integrations. |

**RepoMind · Tencent × SZTU university–industry project · Mar–Sep 2026**<br/>
Worked on coding-agent trace analysis and evaluation, code retrieval, and incremental indexing. This project preceded my Tencent internship.

## Selected projects

| Project | What it does |
| --- | --- |
| **[LaTeX Resume Skill](https://github.com/passionworkeer/latex-resume-skill)** | Evidence-based resume editing, 20 LaTeX templates, a visual editor with real PDF previews, and content/layout checks. |
| **[yt · Shared Memory Bus](https://github.com/passionworkeer/obsidian-shared-memory-bus)** | A local-first MCP runtime that shares structured memory and retrieval across AI tools. |
| **[Attrax / CompliPilot](https://github.com/passionworkeer/attrax)** | Product-image-based compliance research with source-linked findings and exportable evidence. Contributed to retrieval and application delivery. |

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,rust,ts,fastapi,react,redis,mysql,docker,git&amp;perline=10" alt="Python, Go, Rust, TypeScript, FastAPI, React, Redis, MySQL, Docker, Git" />
</p>

**Agent systems:** MCP · Evaluation &amp; regression · Tool use · RAG · Trace analysis · Tree-sitter / AST<br/>
**Backend &amp; data:** Go · Python · TypeScript · SQL · MySQL · Redis · ClickHouse

## Selected recognition

<img src="assets/logos/feishu.svg" alt="Feishu 飞书 — competition platform" width="92" /> &nbsp;
<img src="assets/logos/douyin.svg" alt="Douyin 抖音 — hackathon organizer" width="92" />

- **Runner-up (Second Prize)** — 第二届星瀚杯“全国大学生法律AI应用”创新挑战赛 · CompliPilot · 2026.
- **Track 3, Second Prize** — 抖音 AI 创变者计划 2026 年黑客松联赛（清北哈站）.
- **LabMemory · Team lead** — 2026 AI 先锋未来人才大赛（飞书 × DI-IDEA）.

## Contribution activity

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution graph" src="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake.svg" />
</picture>
</p>
