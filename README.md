<div align="center">

# Jianjun Wang

**AI Application Developer · Data Science @ SZTU · Shenzhen**

Building AI-native products with sharp product instincts and full-stack execution.

[![GitHub](https://img.shields.io/badge/GitHub-passionworkeer-181717?style=flat&logo=github)](https://github.com/passionworkeer)
[![Email](https://img.shields.io/badge/Email-17820577270@163.com-EA4335?style=flat&logo=gmail)](mailto:17820577270@163.com)
[![Visitors](https://komarev.com/ghpvc/?username=passionworkeer&color=brightgreen&style=flat&label=Profile+Views)](https://github.com/passionworkeer)

</div>

---

### 🏆 Recognition

| Award | Role | Year |
|---|---|---|
| Douyin Hackathon — 2nd Place | Team Lead | 2026 |
| National Math Modeling — Provincial 1st | Team Lead | 2025 |
| Huashu Cup Math Modeling — National 1st | Team Lead | 2025 |
| Zhengda Cup — Provincial 1st | — | 2025 |

---

### 💼 Experience

**AI Application Engineer · Shenzhen Linyuan Technology** `2025.10 – 2025.12`

Built a multimodal AI content generation system for cross-border e-commerce visual supply chains.

- Designed high-availability async architecture: `FastAPI + Redis` distributed task queue + WebSocket push + dead-letter retry — **zero crashes** under peak traffic
- Built LLM routing gateway with adapter pattern unifying `Gemini`, `SD`, and other heterogeneous models
- Constructed `LLM-as-a-Judge` evaluation benchmark with Few-shot + CoT prompt optimization — reduced manual intervention by **30%+**

---

### 🔨 Currently Building

**[Twinbuddy](https://github.com/passionworkeer/twinbuddy)** — AI travel companion matching platform

> Core moat: bilateral `LangGraph` avatar negotiation accumulates behavioral data (concession patterns, conflict styles) that competitors cannot replicate by swapping LLMs.

`React + Vite` `FastAPI` `LangGraph` `PostgreSQL` `Redis` `Qdrant` `Claude API`

---

### 📌 Projects

**Tencent × SZTU: AI Code Analysis & Multilingual Repair Benchmark** `2026.03 – present`

> Built a high-difficulty code repair benchmark for internal AI Coding Agents.

- Fine-tuned `Qwen3.5-9B` with LoRA for domain-specific code analysis; built **AST slicing + 3-way RRF fusion** RAG pipeline
- Designed 4-dimensional system-level prompt optimization + adversarial dual-review workflow
- Cross-file code analysis **F1: 0.28 → 0.61 (+120%)**
- Designed `C/E/Q` 3-dimensional continuous scoring + regression penalty — surpassing SWE-bench binary scoring limits
- Built fail-to-pass test suite covering **5 languages × 3 defect dimensions** from scratch

**[obsidian-shared-memory-bus](https://github.com/passionworkeer/obsidian-shared-memory-bus)** — Cross-agent shared memory `2026.01 – present`

> Solves context isolation across AI coding tools (Claude Code, Codex, Cursor, OpenCode).

- `L0–L4` five-layer memory architecture: Event buffer → Durable persistence
- `BM25 + Dense` hybrid retrieval + `FNV-1a32` LSH offline vectorization — **<50ms latency** on 100k-token local libraries
- `MMR (λ=0.7)` diversity reranking + Circuit Breaker + Backpressure — stable at **50+ QPS**

---

### 🧰 Tech Stack

<div align="center">

[![Skills](https://skillicons.dev/icons?i=python,fastapi,nodejs,react,ts,postgres,redis,docker,git,linux)](https://skillicons.dev)

</div>

`LangChain` `LangGraph` `Multi-Agent` `RAG` `LoRA` `MCP` `BM25` `WebSocket` `Prompt Engineering`

---
