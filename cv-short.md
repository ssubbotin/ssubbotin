# Sergey Subbotin

**AI-Augmented Engineering Lead**

Belgrade, Serbia | ssubbotin@gmail.com | [linkedin.com/in/ssubbotin](https://linkedin.com/in/ssubbotin) | [github.com/ssubbotin](https://github.com/ssubbotin) | [medium.com/@sergeysubbotin](https://medium.com/@sergeysubbotin)

---

## Summary

Senior software engineer (24+ years) pivoting into full-time **AI-augmented / "vibe coding" roles**. I bring deep engineering judgement — safety-critical avionics (DO-178C, FAA), large-scale infrastructure at Yandex (millions of RPS), aerospace radar systems — and pair it with a power-user command of Claude Code, MCP servers, and multi-agent orchestration. **265 Claude Code sessions, 176,848 messages, 54,759 tool calls, 209 commits, ~2,150 h** in 2026 alone (Jan–Apr).

**What I can offer your team:**
- Drop-in AI-augmented senior engineer — ship features, reviews, refactors, migrations at a pace teams rarely see.
- Set up LLM-accelerated engineering processes for existing teams: PR-review pipelines, MCP integrations, multi-agent workflows, CLAUDE.md discipline, hooks, custom skills.
- Translate 24 years of "how real engineering works" into guardrails that keep LLM output production-grade in regulated and non-regulated domains alike.

---

## AI-Augmented Development (pivot focus)

**Usage metrics (`/stats` + `/insights` on my own machine, 2026-01-02 → 04-21):**
- **265 sessions, 176,848 messages, 54,759 tool calls, 63 active days, 18.33 B tokens**
- **209 git commits across 109 analyzed sessions, ~2,153 hours** of Claude Code session time
- **Projects touched: 15+** — safety-critical radar (AeroNAV RLMKX), Yandex infra, LLM/ML (flash-moe, bootstrap-llm, cudascope), tooling, personal
- Primary model: **Claude Opus 4.6** (~73% of traffic); also Opus 4.5/4.7, Haiku 4.5, Sonnet 4.6

**What I actually do with it:**
- **PR-review pipelines** — most frequent workflow: fetch diff + prior comments, post structured inline reviews to Gitea via API, rebase + re-review, batch across 2–3 PRs at once.
- **MCP server development** — built production MCP with 20+ tools at Yandex; forked & patched an MCP to fix auth; connected Claude Code to Yandex Wiki, Yandex Tracker, Gitea.
- **Multi-agent orchestration** — parallel sub-agents for cross-repo refactors, C++ style analysis (5 agents at once), monorepo migrations (176 commits in a single session).
- **RAG-enhanced review infrastructure** for Gitea (in progress, Phase 1 shipped).
- **Process authorship** — `CLAUDE.md`, custom skills, PreToolUse/PostToolUse hooks, acceptance-test harnesses, runbooks from diagnostic sessions.
- **Systematic root-cause debugging with LLM assistance** — VLC/fontconfig, powerline on Python 3.14, Qwen3-MoE degeneration, i386 purge, kernel cleanup.

---

## Technical Skills

**Languages:** Python, Go, C/C++, TypeScript, SQL, Protobuf, Java
**Infrastructure:** Docker, Nginx/AWACS, ZooKeeper, RabbitMQ, MongoDB, Redis, PostgreSQL, Elasticsearch
**Cloud & CI/CD:** AWS (EC2, S3), Yandex Cloud, GitHub Actions, Gitea Actions, Jenkins, GitLab CI
**Monitoring:** Grafana, Prometheus, ELK, OpenTelemetry, DataLens
**LLM tooling:** Claude Code, Claude Agent SDK, Anthropic API, MCP protocol, prompt caching, multi-agent / sub-agent patterns, hooks & skills, RAG
**Practices:** Agile/Scrum, Code Review, CI/CD, DO-178C V&V, Mentoring
**Other tools:** LLVM/Clang, IBM DOORS, Hex-Rays IDA Pro, Matlab, React, gRPC, TVM

---

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

### Team Lead — IANS (Aero Navigation Systems) JSC | Mar 2021 – May 2023
*Meteorological systems & UTM for unmanned aircraft — Moscow*
- Rescued a stalled airport meteorological system project; delivered on time with a team grown to 5
- Hired and built a 6-person team for RUTM1 (unmanned traffic management) web service
- Selected stacks (React/Python/Mongo; React/Go/Mongo/RabbitMQ), set up Agile, CI/CD, ELK/Docker

### Senior Developer — Avature | Jun 2017 – Nov 2020
*Human Capital Management SaaS — Buenos Aires, Argentina*
- Evolved in-house test system: 2M tests/day on 2,000 AWS instances
- Doubled tests per machine-hour; cut cloud expenses by more than half
- Built responsive auto-updating UI with extensible templates

### Lead Software Engineer — DC BARS Inc. | Feb 2003 – Mar 2017
*Avionics V&V and certification — Moscow*
- 30+ projects, 10+ aircraft certified by FAA (DO-178B/C)
- 5 years on Honeywell Primus Epic displays; 2 years on Rockwell Collins Pro Line Fusion
- Created a DO-178C qualified toolset: coverage collection, WCET estimation, control flow analysis
- Built Certivision — Eclipse-based requirements/change management system (Scrum Master, 9 engineers)
- Automated test generation saving 30%+ time for certain requirement categories

---

## Open Source

- **LLVM/clang-format** — Merged PR: per-operator granularity for BreakBinaryOperations (2026)
- **flash-moe (fork of danveloper/flash-moe)** — Ported the Metal-only 397B-param MoE inference engine to three additional GPU backends: **CUDA** (61 commits), **ROCm** (46 commits), **AMD APU / Strix Halo** (73 commits, incl. original dp4a + undocumented hipMalloc discoveries), and **MI300 optimization branch** (53 commits). 233 commits of low-level GPU work across four vendors.
- **cudascope** — Self-hosted NVIDIA GPU monitoring with real-time dashboards (Go)
- **redis-ui** — Modern web UI for Redis (JavaScript)
- **zookeeper-ui** — Web UI for Apache ZooKeeper with protobuf support (JavaScript)
- **claude-honk** — Notification sound for Claude Code (Shell)
- **gost-r-54084-2010** — Atmospheric boundary layer models for aerospace (Python)

---

## Education

**MS Mathematics & Computer Science** — National Research Nuclear University MEPhI, 1998–2006
Thesis: Automatic test generation for avionics software using X-boolean logic on MATLAB models

---

## Languages

Russian (native) · English (fluent) · Spanish (basic)
