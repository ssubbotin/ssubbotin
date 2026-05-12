# Hi, I'm Sergey Subbotin

**AI-Augmented Engineering Lead** based in Belgrade, Serbia

24+ years building software — from safety-critical avionics certified by the FAA to cloud infrastructure handling millions of RPS at Yandex. Now pivoting full-time into **AI-augmented / "vibe coding" engineering roles**: shipping at LLM-accelerated pace while keeping output production-grade.

## What I'm doing now

**Team Lead @ AeroNAV** — managing a team of 8 building an airport meteorological radar system. 11 repos, 605+ PRs; built the team's LLM-accelerated engineering process end-to-end (AI-driven PR review pipeline, parallel multi-agent refactors, RAG-enhanced review, Gitea/Redmine MCPs).

**Software Developer @ Yandex (May 2023 – May 2026)** — L3/L7 load balancing control plane orchestrating traffic for millions of RPS. 366 PRs merged adding 122K+ lines, 869 PRs reviewed. Built one of Yandex's first infra MCP servers (20+ tools for natural-language AWACS management).

## Claude Code, by the numbers (2026-01 → 04)

- **265 sessions, 176,848 messages, 54,759 tool calls, 18.33 B tokens, 63 active days**
- **209 git commits** shipped across 109 analyzed sessions, ~2,153 hours of session time
- Primary model: Claude Opus 4.6 (~73% of traffic); also Opus 4.5/4.7, Haiku 4.5, Sonnet 4.6
- 15+ projects touched: safety-critical radar, Yandex infra, LLM/ML systems, tooling, personal

## Tech stack

**Languages:** Python, Go, C/C++, TypeScript, SQL

**LLM tooling:** Claude Code, Claude Agent SDK, Anthropic API, MCP protocol, prompt caching, multi-agent / sub-agent patterns, hooks & skills, RAG

**GPU / low-level:** Apple Metal (read), CUDA 12+, AMD HIP/ROCm, Strix Halo APU (dp4a + hipMalloc), MI300 tuning (aotriton flash-attn, FLA fused recurrent)

**Infrastructure:** Docker, Nginx, ZooKeeper, RabbitMQ, MongoDB, Redis, PostgreSQL, Elasticsearch

**Cloud & CI/CD:** AWS, Yandex Cloud, GitHub Actions, Gitea Actions, Jenkins

**Monitoring:** Grafana, Prometheus, ELK, OpenTelemetry

## Highlights

- **30+ avionics projects**, 10+ aircraft certified by FAA (DO-178B/C)
- **Large-scale distributed systems** — L3/L7 load balancing, 7,000+ balancer migrations, 5 datacenters
- **AI-augmented engineering at scale** — production MCP server (20+ tools), LLM-driven code review pipelines on Gitea, multi-agent orchestration (5 parallel agents for cross-repo refactors, 176-commit monorepo migration in one session), full-stack project bootstrapping from zero to production
- **Mentored 5+ engineers**, served as Scrum Master for 3 years

## Open source

- [**flash-moe**](https://github.com/ssubbotin/flash-moe) — multi-vendor GPU port of the Metal-only inference engine that runs Qwen3.5-397B-A17B (397B-param MoE) on consumer hardware. **233 commits across four branches**: CUDA (61), ROCm (46), AMD APU / Strix Halo (73, incl. dp4a + undocumented hipMalloc discoveries), and MI300 optimization (53, aotriton flash-attn + FLA fused recurrent). [Article: Running 397B on a single RTX 4090](https://gist.github.com/ssubbotin/e778f97ebf1f76b8fd423c0bc3961a1a).
- [**libfprint**](https://gitlab.freedesktop.org/libfprint/libfprint/-/merge_requests/570) — new driver for FPC Disum USB fingerprint sensors (FPC1022). TLS-PSK encrypted USB protocol, SIFT-based matching for small-area sensors.
- [**LLVM/clang-format**](https://github.com/llvm/llvm-project/pull/181051) — merged PR: per-operator granularity for BreakBinaryOperations
- [**cudascope**](https://github.com/ssubbotin/cudascope) — self-hosted NVIDIA GPU monitoring (Go)
- [**redis-ui**](https://github.com/ssubbotin/redis-ui) — modern web UI for Redis
- [**zookeeper-ui**](https://github.com/ssubbotin/zookeeper-ui) — web UI for Apache ZooKeeper with protobuf support
- [**gost-r-54084-2010**](https://github.com/ssubbotin/gost-r-54084-2010) — atmospheric boundary layer models for aerospace (Python)

## Links

- [CV (short)](cv-short.md) | [CV (full)](cv-full.md)
- [LinkedIn](https://linkedin.com/in/ssubbotin)
- [Medium](https://medium.com/@sergeysubbotin)
