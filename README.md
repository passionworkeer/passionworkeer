[Portfolio](https://wangjianjun.xyz) · [Open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Apassionworkeer+-user%3Apassionworkeer) · [Projects](https://github.com/passionworkeer?tab=repositories) · [Writing](https://passionworkeer.github.io/passionworkeer/)

## Contributing to

These are upstream projects I contribute to, not projects I own; the badges show each repository's own live star and fork counts, not personal metrics. My work is mostly correctness at the boundaries of shells, RAG pipelines and agent runtimes: reproduce a hard-to-hit edge case, narrow the fix to its cause, and add regression coverage where it fits. The same habit runs through the rest of my work, from agent evaluation and failure diagnosis to backend data services for ingestion, analytical queries and usage metering.

| Upstream project | Project scale | What I work on |
| --- | --- | --- |
| <img src="assets/logos/nushell.svg" alt="" width="22" /> **[nushell/nushell](https://github.com/nushell/nushell)** | ![nushell stars](https://img.shields.io/github/stars/nushell/nushell?style=for-the-badge&label=stars) ![nushell forks](https://img.shields.io/github/forks/nushell/nushell?style=for-the-badge&label=forks) | Command-name validation against numeric, duration, date and range literals; relative-path traversal and negated character classes in the experimental glob command; time-zone offsets with seconds in date conversions; and documentation updates to the Chinese-language book. |
| **[HKUDS/LightRAG](https://github.com/HKUDS/LightRAG)** | ![LightRAG stars](https://img.shields.io/github/stars/HKUDS/LightRAG?style=for-the-badge&label=stars) ![LightRAG forks](https://img.shields.io/github/forks/HKUDS/LightRAG?style=for-the-badge&label=forks) | Unreadable image-cache manifests treated as cache misses so document parsing no longer aborts early; regression tests and an initial fix for the WebUI multiline-input caret race, whose final implementation was completed by the maintainer. |
| **[agentscope-ai/QwenPaw](https://github.com/agentscope-ai/QwenPaw)** | ![QwenPaw stars](https://img.shields.io/github/stars/agentscope-ai/QwenPaw?style=for-the-badge&label=stars) ![QwenPaw forks](https://img.shields.io/github/forks/agentscope-ai/QwenPaw?style=for-the-badge&label=forks) | Startup diagnostics for unusable plugin dependency directories in restricted deployments, while keeping read-only roots with prepared subdirectories working. |

Other upstream projects I contribute to are pinned on this profile, where GitHub renders their star and fork numbers natively; the [open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Apassionworkeer+-user%3Apassionworkeer) link opens the full, verifiable record.

## Experience

| When | Role | Focus |
| --- | --- | --- |
| **Oct 2026–present** | <img src="assets/logos/tencent.svg" alt="Tencent" width="72" /> · Backend Development Intern | Monitoring data services: ingestion, analytical queries, usage metering, and data consistency. |
| Aug–Oct 2026 | <img src="assets/logos/kuaishou.svg" alt="Kuaishou" width="72" /> · Agent Development Intern | Design-agent evaluation, structured Figma editing, MCP integration, and failure diagnosis. |
| Mar–Sep 2026 | **RepoMind** · Tencent × SZTU industry project | Coding-agent trace analysis and evaluation, code retrieval, and incremental indexing. |
| Mar–Jul 2026 | <img src="assets/logos/bananain.svg" alt="Bananain" width="72" /> · AI Application Engineer | AIGC visual workflows, design plugins, and enterprise agent integrations. |

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
**Agent &amp; data:** MCP · RAG (BM25 + FAISS hybrid) · evaluation and regression harnesses · trace analysis · tree-sitter / AST · FastAPI · MySQL · Redis · ClickHouse<br />
**Delivery:** React · TypeScript · Figma · Adobe UXP · Playwright · pytest · Docker · GitHub Actions
