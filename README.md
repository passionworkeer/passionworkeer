# Jianjun Wang

**AI Agent Engineer · Evaluation · Backend Systems**<br />
Backend Development Intern @ **Tencent** · Data Science @ **Shenzhen Technology University**

I build agents that use tools, produce verifiable results, and fit into real workflows.

[Portfolio](https://wangjianjun.xyz) · [Open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Apassionworkeer+-user%3Apassionworkeer) · [Projects](https://github.com/passionworkeer?tab=repositories) · [Writing](https://passionworkeer.github.io/passionworkeer/)

<img src="assets/logos/tencent.svg" alt="Tencent" width="104" /> <img src="assets/logos/kuaishou.svg" alt="Kuaishou" width="104" /> <img src="assets/logos/bananain.svg" alt="Bananain" width="104" />

<sub>Current: Tencent · Previously: Kuaishou &amp; Bananain</sub>

---

## Now

- **Backend Development Intern @ Tencent** — monitoring data services: ingestion, analytical queries, usage metering, and data consistency.
- **Upstream Rust** — fixes and regression coverage for storage and agent-transport internals: Apache OpenDAL, MCP Rust SDK, Nushell.

## Recent open-source contributions

| Project | Change | Merged |
| --- | --- | --- |
| <img src="assets/logos/opendal.svg" alt="Apache OpenDAL" width="88" /><br /><sub>**Apache OpenDAL**</sub> | [#8429 — avoid initializing unused writers on abort](https://github.com/apache/opendal/pull/8429). Aborting a lazy Fs writer no longer initializes its inner writer, so cancelling before the first write cannot truncate an existing file or create the target. Seven new tests against real temporary filesystems; the official filesystem behavior suite (130 tests) passes with and without `atomic_write_dir`. | **Oct 30, 2026** |
| <sub>**MCP Rust SDK**</sub> | [#1382 — match explicit HTTP media types and Accept quality values](https://github.com/modelcontextprotocol/rust-sdk/pull/1382). Streamable HTTP now parses complete media-type essences case-insensitively, inspects every `Accept` field value, and honors quality weights (RFC 9110). 19 real HTTP scenarios in one regression test; 378 library tests pass. | **Oct 30, 2026** |
| <img src="assets/logos/nushell.png" alt="Nushell" width="24" /><br /><sub>**Nushell**</sub> | [#19348 — traverse explicit relative paths](https://github.com/nushell/nushell/pull/19348). Experimental `dc-glob` now searches the intended directory for `./*.txt`, `../*.txt`, and `../**`, and returns the matching directory for `.` and `..`. | **Oct 29, 2026** |
| <img src="assets/logos/nushell.png" alt="Nushell" width="24" /><br /><sub>**Nushell**</sub> | [#19309 — honor negated character classes](https://github.com/nushell/nushell/pull/19309). `[!f]*` now excludes names beginning with `f`, with regression coverage for traversal, ranges, Unicode, and case handling. | **Oct 25, 2026** |

## Experience

| When | Role | Focus |
| --- | --- | --- |
| **Oct 2026–present** | **Tencent** · Backend Development Intern | Monitoring data services: ingestion, analytical queries, usage metering, and data consistency. |
| Aug–Oct 2026 | **Kuaishou** · Agent Development Intern | Design-agent evaluation, structured Figma editing, MCP integration, and failure diagnosis. |
| Mar–Sep 2026 | **RepoMind** · Tencent × SZTU industry project | Coding-agent trace analysis and evaluation, code retrieval, and incremental indexing. |
| Mar–Jul 2026 | **Bananain** · AI Application Engineer | AIGC visual workflows, design plugins, and enterprise agent integrations. |

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

**Languages:** Go · Rust · Python · TypeScript · SQL<br />
**Agent systems:** MCP · tool use · RAG (BM25 + FAISS hybrid retrieval) · LangGraph · NLI citation gating · evaluation &amp; regression harnesses · trace analysis · tree-sitter / AST<br />
**Backend &amp; data:** FastAPI · MySQL · Redis · ClickHouse<br />
**Product &amp; design tooling:** React · TypeScript · Figma (structured editing) · Adobe UXP plugins<br />
**Testing &amp; delivery:** Playwright · pytest · Docker · Git · GitHub Actions

## Selected recognition

<img src="assets/logos/feishu.svg" alt="Feishu — competition platform" width="92" /> &nbsp;
<img src="assets/logos/douyin.svg" alt="Douyin — hackathon organizer" width="92" />

- **Runner-up (Second Prize)** — 2nd Xinghan Cup · National Legal AI Innovation Challenge · CompliPilot · 2026.
- **Track 3, Second Prize** — Douyin AI Changemakers 2026 Hackathon League · TwinBuddy · 2026.
- **Annual Top 40 · team lead** — 2026 AI Pioneer Future Talent Competition (Feishu × DI-IDEA) · LabMemory · 2026.

## Contribution activity

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution graph" src="https://raw.githubusercontent.com/passionworkeer/passionworkeer/output/github-contribution-grid-snake.svg" />
</picture>
</p>
