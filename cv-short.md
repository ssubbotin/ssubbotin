# Sergey Subbotin

**AI-Augmented Engineering Lead**

Belgrade, Serbia | ssubbotin@gmail.com | [linkedin.com/in/ssubbotin](https://linkedin.com/in/ssubbotin) | [github.com/ssubbotin](https://github.com/ssubbotin)

## Summary

Senior software engineer (24+ years) pivoting into full-time **AI-augmented / "vibe coding" roles**. Deep engineering judgement — safety-critical avionics (DO-178C, FAA), Yandex-scale infrastructure (millions of RPS), aerospace radar — paired with power-user command of Claude Code, MCP servers, and multi-agent orchestration. **265 Claude Code sessions, 176K messages, 55K tool calls, 209 commits, ~2,150 h, 18.3 B tokens — Jan–Apr 2026 alone** (own `/stats` + `/insights`; primary model Opus 4.6, ~73% of traffic).

**What I can offer:** drop-in AI-augmented senior engineer shipping features/reviews/refactors/migrations at LLM-accelerated pace; OR set up your team's LLM-accelerated engineering process from scratch — PR-review pipelines, MCP integrations, multi-agent workflows, `CLAUDE.md` discipline, hooks, custom skills, RAG-enhanced review. 24 years of "how real engineering works" as the guardrails that keep LLM output production-grade.

## Technical Skills

**Languages:** Python, Go, C/C++, TypeScript, SQL, Protobuf, Java
**LLM tooling:** Claude Code, Claude Agent SDK, Anthropic API, MCP protocol, prompt caching, multi-agent / sub-agent patterns, hooks & skills, RAG; PR-review pipelines on Gitea, monorepo-scale refactors (176 commits in one session)
**Infrastructure:** Docker, Nginx, ZooKeeper, RabbitMQ, MongoDB, Redis, PostgreSQL, Elasticsearch; AWS, Yandex Cloud; GitHub/Gitea Actions, Jenkins, GitLab CI; Grafana, Prometheus, ELK, OpenTelemetry
**Practices & tools:** Agile/Scrum, Code Review, CI/CD, DO-178C V&V, Mentoring; LLVM/Clang, IBM DOORS, Hex-Rays IDA Pro, Matlab, React, gRPC, TVM

## Experience

### Team Lead — AeroNAV (Navigator LLC) | Jan 2025 – Present
*Airport meteorological radar complex (RLMKX) — Remote*
- Managing a team of 8 (3 backend, 1 frontend, 1 UX/UI, 1 analyst, 1 expert) building a radar control and monitoring system
- 11 repositories, ~2,900 commits, 605+ pull requests; stack: C++, nesC, JS/TS, Python, Docker
- Set up CI/CD, code review process, and DevOps infrastructure from scratch
- **Built the team's LLM-accelerated engineering process end-to-end**: AI-driven PR review pipeline (70 Claude Code sessions / 18K messages on this one project), parallel multi-agent cross-repo refactors, RAG-enhanced review infrastructure, Gitea/Redmine MCPs

### Software Developer — Yandex | May 2023 – May 2026
*AWACS — traffic balancing control plane for millions of RPS — Belgrade, Serbia*
- Delivered 366 merged PRs (122K+ lines), reviewed 869 PRs across a cross-functional team
- Migrated 750+ L7 balancers to Deploy (270 production); migrated 7,000+ to new Unified Agent
- Accelerated API by 30% (caching, SAGA pattern); eliminated 2,000+ flaky tests (30→20 min suite)
- Implemented TVM auth (358+ balancers), OpenTelemetry tracing, gRPC support (100+ upstreams)
- **Early adopter of AI-augmented development at Yandex**: built a production MCP server with 20+ tools for natural-language AWACS management; published internal posts on AI-driven workflows
- Mentored 5+ bootcamp interns; led daily standups during lead's absence

### Team Lead — IANS JSC | Mar 2021 – May 2023
*Meteorological systems & UTM for unmanned aircraft — Moscow*
- Rescued a stalled airport meteorological project; delivered on time with a team grown to 5
- Hired and built a 6-person team for RUTM1 (unmanned traffic management); selected stacks (React/Python/Mongo; React/Go/Mongo/RabbitMQ), set up Agile, CI/CD, ELK/Docker

### Senior Developer — Avature | Jun 2017 – Nov 2020
*Human Capital Management SaaS — Buenos Aires, Argentina*
- Evolved in-house test system to 2M tests/day on 2,000 AWS instances; doubled tests per machine-hour and cut cloud spend by >50%
- Built responsive auto-updating UI with extensible templates

### Lead Software Engineer — DC BARS Inc. | Feb 2003 – Mar 2017
*Avionics V&V and certification — Moscow*
- 30+ projects, 10+ aircraft FAA-certified (DO-178B/C); 5 yrs Honeywell Primus Epic, 2 yrs Rockwell Collins Pro Line Fusion
- Built DO-178C qualified toolset (coverage, WCET, control flow analysis) and Certivision — Eclipse-based requirements/change management system (Scrum Master, 9 engineers); automated test generation saving 30%+ on some requirement categories

## Open Source

- **flash-moe (fork)** — Ported a Metal-only 397B-param MoE inference engine to **CUDA** (61 commits), **ROCm** (46), **AMD APU / Strix Halo** (73, original dp4a + undocumented hipMalloc discoveries), and **MI300-opt** (53). 233 commits of low-level GPU work across four vendors.
- **LLVM/clang-format** — Merged PR: per-operator granularity for BreakBinaryOperations (2026)
- **cudascope** — Self-hosted NVIDIA GPU monitoring (Go); **redis-ui** / **zookeeper-ui** — modern web UIs (JS); **gost-r-54084-2010** — atmospheric boundary layer models (Python)

## Education & Languages

**MS Mathematics & Computer Science** — National Research Nuclear University MEPhI, 1998–2006 (thesis: automatic test generation for avionics software using X-boolean logic on MATLAB models). **Languages:** Russian (native) · English (fluent) · Spanish (basic).
