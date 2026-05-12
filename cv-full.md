# Sergey Subbotin

**AI-Augmented Engineering Lead**

Belgrade, Serbia | ssubbotin@gmail.com
[linkedin.com/in/ssubbotin](https://linkedin.com/in/ssubbotin) | [github.com/ssubbotin](https://github.com/ssubbotin) | [medium.com/@sergeysubbotin](https://medium.com/@sergeysubbotin)

---

## Summary

Senior software engineer (24+ years) actively pivoting into full-time **AI-augmented / "vibe coding" engineering roles**. My value proposition: the combination that makes LLM-driven development actually ship — **deep engineering judgement from a quarter-century of real systems** (safety-critical avionics with FAA/DO-178C certification, Yandex-scale infrastructure at millions of RPS, aerospace radar systems) **plus a power-user command of Claude Code, MCP, and multi-agent orchestration** proven on 18 billion tokens of personal usage in four months.

**What I'm looking for.** Roles where I can either (a) operate as a drop-in AI-augmented senior engineer shipping features / reviews / refactors / migrations at a pace that is visibly higher than a conventional team can match, or (b) help established teams and companies **set up and run their own LLM-accelerated engineering processes** — PR-review pipelines, MCP integrations, multi-agent workflows, CLAUDE.md discipline, hooks, custom skills, test-first self-healing loops, RAG-enhanced code review.

Career progression: Engineer → Scrum Master → Team Lead → PM → hands-on Technical Lead → AI-Augmented Lead. Always close to the code, always scaling impact through people, process, and — now — tooling. Worked in multinational teams across Russia, Argentina, and Serbia.

Rare combination of **safety-critical domain knowledge** (DO-178C, FAA certification, 30+ avionics projects, 10+ aircraft certified), **big-tech infrastructure at scale** (millions of RPS, thousands of servers), **and power-user AI-augmented development**. Passionate about automation, identifying growth points, and building tools that make teams more effective — now with LLMs as the force multiplier.

---

## Technical Skills

### Languages
**Primary:** Python, Go, C/C++
**Proficient:** SQL, Protobuf, Java
**Historical:** PHP, Delphi, x86 Assembler, VBA, Svelte

### Infrastructure & DevOps
- **Containers:** Docker, Docker Compose, Docker Swarm
- **Orchestration:** ZooKeeper, RabbitMQ, Nginx/AWACS (L3/L7)
- **Databases:** MongoDB, Redis, PostgreSQL, MySQL, Elasticsearch, SQLite
- **CI/CD:** GitHub Actions, Gitea Actions, Jenkins, GitLab CI, Bamboo
- **Cloud:** AWS (EC2 spot fleets, S3), Yandex Cloud, Google App Engine

### Monitoring & Observability
Grafana, Prometheus, ELK (Elasticsearch, Logstash, Kibana), OpenTelemetry, Yandex Monitoring, DataLens

### Frameworks & Tools
React, Node.js, Svelte, gRPC, TVM, Proxy Protocol, LLVM/Clang, IBM DOORS, IBM ClearCase, Hex-Rays IDA Pro, Matlab, Jinja2

### GPU / Low-Level
Apple Metal (reference reading), CUDA 12+, AMD HIP / ROCm, AMD APU (Strix Halo dp4a + hipMalloc), MI300 tuning (aotriton flash-attn, FLA fused recurrent kernels). Hand-written compute kernels for 4-bit/2-bit dequant matvec, fused attention (Q@K^T, softmax, scores@V), RMS norm, RoPE, SwiGLU, MoE combine. LLM inference engine internals (SSD expert streaming, KV cache, OpenAI-compatible SSE server, tool calling).

### AI-Augmented Development (primary focus area)
- **Claude Code** as a daily engineering partner: 265 sessions, 176,848 messages, 54,759 tool calls, 18.33 B tokens across 63 active days (2026-01 to 04).
- **Models used:** Opus 4.6 (~73% of traffic), Opus 4.5, Opus 4.7, Haiku 4.5, Sonnet 4.6.
- **MCP server development:** production MCP with 20+ tools for AWACS API at Yandex; MCP integrations for Yandex Wiki, Yandex Tracker, internal Gitea; forked and patched an MCP to fix broken auth.
- **Multi-agent orchestration:** parallel sub-agents for cross-repo code reviews, C++ style analysis (5 agents simultaneously), monorepo migrations (176 commits in one session).
- **RAG-enhanced PR review infrastructure** for internal Gitea (in progress, Phase 1 shipped).
- **Process authorship:** `CLAUDE.md` design, custom slash-command skills, PreToolUse / PostToolUse hooks, TaskCreate/TaskUpdate discipline (659 combined in analyzed sessions), acceptance-test harnesses, runbooks emitted from diagnostic sessions.
- **Project bootstrapping from zero:** full-stack apps delivered through production using AI-augmented workflows (Go backend, TypeScript frontend, Android/Kotlin with MockWebServer/Hilt E2E tests).

### Practices
Agile/Scrum (7 years + 3 years as Scrum Master), Code Review, CI/CD, DO-178B/C Verification & Validation, Pair Programming, Mentoring, **LLM-accelerated engineering process design for teams**

---

## Experience

### Team Lead — AeroNAV (Navigator LLC)
**Jan 2025 – Present** | Remote (Contract)
*Airport meteorological radar complex (RLMKX)*

Project Manager and Team Lead for the RLMKX radar control and monitoring system development.

**Team:** 8 people — 3 backend developers, 1 frontend developer, 1 UX/UI designer, 1 analyst, 1 expert

**Key contributions:**
- Architected and oversee development across 11 repositories (~2,900 commits, 605+ pull requests)
- Technology stack: C++, nesC, JavaScript/TypeScript, Python, CMake, Docker
- Set up CI/CD pipelines (Gitea Actions), code review process, and DevOps infrastructure from scratch
- Integration with Redmine issue tracker; established development workflows and team onboarding
- Managing hiring, performance reviews, and cross-functional coordination

**LLM-accelerated engineering process — built and run end-to-end on this project:**
- Dominant single project in my Claude Code usage: **70 sessions / 18,083 messages** on RLMKX alone over ~4 weeks (2026-03 → 04) — the bulk of 209 shipped commits and 32 structured code reviews in analyzed sessions came from here.
- **AI-driven PR review pipeline** on Gitea: Claude fetches the diff + prior review comments, produces a structured review with inline comments and REQUEST_CHANGES status when warranted, then rebases and applies review fixes in the same session. Standard path for ~20 "Code Review & PR Management" sessions.
- **Parallel multi-agent workflows** for cross-repo tasks: 5 agents at once for C++ style analysis; one-shot monorepo migration delivering 176 commits in a single session; coordinated refactors across 3 repos with linked PRs.
- **RAG-enhanced PR review infrastructure** (pr-agent services, Phase 1 shipped) — the seed for a fully asynchronous review pipeline driven by Gitea webhooks.
- **MCP integrations** for Gitea, Redmine, and internal tracking; Redmine end-to-end integration built via AI-augmented workflow (backend + frontend + migrations + docs).
- **Team process authorship:** CLAUDE.md per-repo, custom slash skills for the recurring review loop, PreToolUse / PostToolUse hooks for clang-format and CWD safety, runbooks from diagnostic sessions.

---

### Software Developer — Yandex
**May 2023 – May 2026** | Belgrade, Serbia (Hybrid)
*AWACS — control plane orchestrating load balancing of millions of requests per second to internal and external Yandex services*

**Contribution volume (Arcadia monorepo):**
- 366 merged PRs, 446 commits, 122,000+ lines added, 2,787 files changed
- 869 PRs reviewed from teammates
- 165+ new features implemented
- Stack: Python (1,244 files), Jinja2 (319), YAML (432), Lua (251), Protobuf (84), Go (12)

**Major achievements:**

*L7 Balancers in Deploy*
- Designed migration plan, built migration tooling, defended design at strategy session
- Migrated 750+ L7 balancers to Deploy (270 production), including complex multi-datacenter setups
- Early-adopted by Maps, E-commerce, and RideTech teams

*Infrastructure at Scale*
- Migrated 7,000+ balancers to new Unified Agent versions across SAS, VLA, MAN, KLG, MSK datacenters
- Introduced TVM authentication across 358+ balancers
- Implemented OpenTelemetry tracing and gRPC support (100+ upstreams)
- Built automated export of 1.5M+ AWACS entities to IDP
- Drove 46 balancer configuration changes and 40 deployment/release cycles

*Performance & Reliability*
- Accelerated AWACS API by 30% through caching, SAGA pattern, and ZooKeeper-to-cache migration
- Eliminated 2,000+ flaky tests; reduced test suite from 30 to 20 minutes using mongomock
- Implemented matcher map feature (adopted by 50+ namespaces)
- Added Proxy Protocol support, .com domain WebAuth, PCI_DSS cipher presets
- Resolved 150+ critical bugs (BALANCERSUPPORT); 101 tasks closed in one review cycle
- New alerting templates for E-commerce and RideTech; migrated 3,710 namespaces

*Innovation & AI*
- **Built a production MCP server with 20+ tools for LLM-powered AWACS API management** — enabling engineers to query and manage balancers, namespaces, and certificates through natural language. One of Yandex's first infra MCPs.
- Created SAT solver prototype for go.mod dependency resolution in monorepo (adopted into tooling)
- Developed auto-changelog generation for balancer macros (drove 5K+ balancer upgrades)
- Built state machine visualization scripts (Mermaid diagrams)
- **Early adopter of AI-augmented development at Yandex**; published internal blog posts on AI-driven workflows; helped shape internal adoption patterns

*Documentation & Mentoring*
- Supported technical writer: reviewed and improved 30+ documentation PRs
- Mentored 5+ bootcamp interns (sakost, borzenkoanton, smyshand, balabanovfm, Kirill Pavlov)
- Led daily standups during lead's absence
- Published internal blog posts on debugging, log export, and test acceleration

**Colleague feedback:**
> "Mission critical feature... everything was done in tight deadlines." — Roman Volchanskiy (trusted TVM sources)
> "Matcher Map is just an excellent thing, greatly improving UX." — Evgeny Kharrasov (Maps team)
> "The migration mechanism is awesome, will save many man-hours." — Vadim Mazaev (Deploy migration)
> "Results of acceleration are clearly visible, very cool result!" — Polina Lukina (API performance)

---

### Team Lead — International Aero Navigation Systems Concern (IANS), JSC
**Mar 2021 – May 2023** (2 yrs 3 mos) | Moscow
*Aeronautical technologies and R&D for aviation*

Project management, technical leadership, and DevOps support for two projects:

**Meteorological Airport Information System** (delivered)
- Rescued a stalled project with only 1 junior frontend developer
- Grew team to 5 developers from other projects
- Selected stack (JavaScript, React, Python, MongoDB), designed architecture
- Set up linting, unit testing, and CI/CD from scratch
- Project delivered on time

**RUTM1 — Russian Unmanned Aircraft Traffic Management Web Service**
- Hired and built a team of 6 (backend, frontend, QA, UX/UI)
- Selected stack (TypeScript, React, Golang, MongoDB, RabbitMQ), designed architecture
- Set up full development process from scratch

**Process improvements:**
- Introduced Agile (Scrum) framework with sprint-based work
- Introduced performance reviews to the company
- Set up ELK, Grafana/Prometheus/Alertmanager, Docker Swarm infrastructure

---

### Senior Developer — Avature
**Jun 2017 – Nov 2020** (3 yrs 6 mos) | Buenos Aires, Argentina
*Privately held Human Capital Management SaaS company*

Evolved and maintained in-house test automation system processing 2 million tests daily on Amazon AWS using 2,000 instances at high load.

**Key achievements:**
- Doubled the number of tests run per machine-hour
- Decreased test system cloud expenses by more than half
- Built responsive, auto-updating UI extendable with templates
- Mastered Ubuntu and Windows server spot fleet creation from scratch
- UI/UX/backend improvements reducing content delivery delays

**Recommendations:**
> "When facing any problem he goes deep to understand its root, in order to come up with a great solution from both technical and functional point of view. Super dedicated to his job, he has really made a difference with great impact." — Guillermo Sabbatella, Director of Engineering

> "Sergey is great at both generating new ideas and implementing new things. He is used to create software that exceeds users expectations and he does it by ticking all the boxes good software is supposed to have on quality, maintainability and security." — Juanleon Lahoz, DevOps VP

---

### Lead Software Engineer — DC BARS Inc.
**Feb 2003 – Mar 2017** (14 yrs 2 mos) | Moscow
*Engineering and IT services in avionics software development, Verification & Validation, and certification support*

**Career highlights:** 30+ finished projects, 10+ aircraft certified by FAA

#### Honeywell Primus Epic Display Systems (Feb 2003 – Feb 2008, 5 years)
*4 months on-site at Honeywell*
- Low-level requirement-based tests development and support
- System-level (integration) tests development
- Run for score, test witnessing
- Structural coverage collection and analysis
- Formal inspections of requirements, code, and tests
- On-site training and support; trained team in Moscow
- Project management for small teams (2–15 engineers)

#### Rockwell Collins Pro Line Fusion Avionics (Feb 2008 – Apr 2010, 2 years)
*7 months on-site at Rockwell Collins*
- Same scope as Honeywell, plus low-level requirements development

#### Certivision — Requirements & Change Management System (Apr 2010 – Jul 2013, 3 years)
- Developed Eclipse-based system integrating version management with change management and formal inspection support (DO-178B)
- Eclipse plugin development (Java, some C++)
- Served as Scrum Master for an agile team of 9 engineers
- System architecture proposal and review

#### Data Download Facility for Linx Laser Coders (Feb 2013 – Sep 2013)
- Developed software for printing customer data using Linx laser coders
- Hardware communication adapter development and improvements
- On-site verifications and customer demonstrations

#### WCET Calculation Tool (Jul 2013 – Dec 2013)
- System architecture development from scratch
- Built instrumentation tool based on Clang compiler frontend (C++, STL)
- Profiling backend and analyzer frontend development

#### DO-178C Coverage Collection Toolset (Jan 2014 – Nov 2016, 3 years)
- Created complete qualified toolset for DO-178C Level A certification
- Coverage collection, worst-case execution time estimation, heap/stack usage analysis, control flow analysis
- Built on experience from WCET tool; initiated the project and sold it to management

**QA Automation:**
- Conceived, sold to management, and implemented a tool automating routine test development
- Saved 30%+ time for certain requirement categories

**Recommendation:**
> "He has a very short learning curve and in almost no time you will have a solution or recommendations — he is equally capable of seeing the whole picture and dig deep into details of all tasks assigned to him. He perfectly works autonomously and as a part of a big team." — Alexander Bogdanov, Director of Business Development

---

### Software Developer — RUSIST Security
**Apr 2001 – Feb 2003** (1 yr 11 mos) | Moscow
*CCTV video monitoring systems*

- BT878 chipset driver development (C++, Windows DDK, SoftIce, DirectShow)
- CCTV surveillance application development (COM, Delphi)
- Updated drivers to achieve 25 fps grabbing rate
- Developed SDK for integration with other surveillance systems
- Improved network exchange rate and overall system stability

---

## Open Source Contributions

### LLVM / clang-format (2026)
**Merged PR:** [Add per-operator granularity for BreakBinaryOperations](https://github.com/llvm/llvm-project/pull/181051)

### flash-moe — multi-vendor GPU ports (2026, fork of [danveloper/flash-moe](https://github.com/danveloper/flash-moe))

Upstream is a Metal-only inference engine that runs the 397B-parameter Qwen3.5 MoE model on an M3 Max MacBook at 4.4+ tok/s using hand-written Metal shaders and SSD expert streaming. I **ported the engine to three additional GPU backends** and published an optimization branch for AMD MI300:

| Branch | Target | Commits | Highlights |
| --- | --- | ---: | --- |
| `cuda` | NVIDIA (CUDA 12.8+, cuFile) | 61 | Full backend port: 4-bit/2-bit dequant matvec, RoPE, fused attention, MoE combine+norm, OpenAI-compatible HTTP server |
| `rocm` | AMD discrete (HIP/ROCm) | 46 | Complete ROCm port; uncovered and fixed a GatedDeltaNet key-head mapping bug; resolved WARP_SIZE host/device agreement on ROCm |
| `apu` | AMD APU / Strix Halo | 73 | Original contributions: **dp4a kernel tricks** and **undocumented hipMalloc memory-API discoveries** on Strix Halo — published as a paper section and standalone article |
| `mi300-opt` | AMD MI300 tuning | 53 | FLA fused_recurrent_gated_delta_rule port to HIP, aotriton flash-attention integration, VRAM cache tuning |

**233 commits total** across four branches of low-level GPU work, spanning three GPU vendors (Apple, NVIDIA, AMD) and four hardware targets. Demonstrates portability of the "hand-written compute kernels + SSD expert streaming + trust-the-OS-page-cache" thesis beyond Apple Silicon.

### Personal Projects
- **BORODA** — Requirements management system for DO-178C/KT-178C (TypeScript)
- **cudascope** — Self-hosted NVIDIA GPU monitoring with real-time dashboards (Go)
- **gost-r-54084-2010** — Atmospheric boundary layer models for aerospace (Python)
- **redis-ui** — Modern web UI for Redis (JavaScript)
- **zookeeper-ui** — Web UI for Apache ZooKeeper with protobuf support (JavaScript)
- **claude-honk** — Notification sound for Claude Code (Shell)
- **OpenScrum** — Online Scrum board (ActionScript, 2013)


---

## AI-Augmented Development — Detailed Metrics & Capabilities (2025 – present)

This is my primary focus area and the role I'm pivoting into. The numbers below are from my own `~/.claude/stats-cache.json` and `/insights` outputs, not estimates — see `claude-insights/` in this repo for the raw reports (`stats.md`, `insights.md`, `insights-report-2026-04-21.html`).

### By the numbers

**Global usage (2026-01-02 → 2026-04-20, from `/stats`):**

| Metric | Value |
| --- | ---: |
| Total sessions | **265** |
| Total messages | **176,848** |
| Total tool calls | **54,759** |
| Active days | **63** |
| Grand total tokens | **18.33 B** |
| Longest single session | 3,812 messages / ~59 min |
| Primary model | Claude Opus 4.6 (~73% of traffic) |

**Analyzed-session summary (2026-02-18 → 2026-04-21, from `/insights`):**

| Metric | Value |
| --- | ---: |
| Sessions analyzed | 109 of 118 |
| Messages in analyzed sessions | 1,646 |
| Claude Code session time | ~2,153 hours |
| Commits shipped in analyzed sessions | **209** |
| Projects touched on this machine | **15+** |

### Project portfolio

Claude Code has been applied across a genuinely broad portfolio — not a single stack:

| Domain | Projects |
| --- | --- |
| Safety-critical / radar | AeroNAV RLMKX (70 sessions — dominant single project), rlmkx-wsrmc, rms-navigator |
| Cloud / infra | AWACS at Yandex (MCP server with 20+ tools), tailscale-gnome-qs |
| LLM / ML systems | flash-moe, bootstrap-llm, cudascope, yawiki-dump |
| Tooling / automation | sputnik, hhru, visa-italia, o2-membrane-project |
| Personal / utility | cv (this repo), happy-vac |

### Workflow areas (from `/insights`)

| Area | Sessions | Pattern |
| --- | ---: | --- |
| Code Review & PR Management | 20 | Gitea PR reviews with prior-comment incorporation, inline comments, REQUEST_CHANGES, rebase-and-refix loops |
| Linux sysadmin / Ubuntu upgrade recovery | 8 | Real root-cause diagnosis (VLC/fontconfig, powerline on Python 3.14, i386 purge, kernel cleanup) |
| Feature development & integrations | 7 | End-to-end Redmine integration, SCM fixes, MCP/LLM connectivity, RAG-enhanced PR review |
| Debugging & diagnostics | 6 | Qwen3-MoE degeneration, everest-server crash loops, self-update shell hash shadowing |
| Networking & infrastructure setup | 4 | WireGuard → Tailscale pivot on CGNAT, OpenWRT/MTS CPE bridge mode, Yandex Wiki/Tracker MCPs |

### How I work with LLMs (interaction style, self-observed)

- **Terse, directive, compound requests** — I state the goal and let Claude execute end-to-end ("review PR X incorporating prior comments, then post"). Bash-heavy (5,601 calls in 49 sessions) and 209 commits across analyzed sessions bear this out.
- **Surgical intervention, not micromanagement** — 43 of 49 sessions finished mostly or fully achieved despite iteration events; I trust the try-fix-retry loop.
- **Pragmatic pivots when blocked** (WireGuard → Tailscale on CGNAT; WebFetch → curl + API token when internal servers aren't reachable; patch the system file directly when upstream is broken).
- **Artifact discipline** — CLAUDE.md per repo, memory notes across MCP integrations, saving `/stats` and `/insights` reports as source data, 659 combined TaskCreate/TaskUpdate calls in analyzed sessions for structured progress visibility.

### What I can bring to your team

- **Operate as a drop-in AI-augmented senior engineer** — ship features, reviews, refactors, migrations at a pace where a single engineer + Claude measurably outpaces a conventional small team on many workloads.
- **Set up your team's LLM-accelerated engineering process from scratch**: CLAUDE.md, custom skills, hooks, MCP servers for your internal tools (issue tracker, VCS, wiki, observability), RAG-enhanced review pipelines, multi-agent orchestration patterns for refactors and migrations.
- **Transplant what already works on my projects**: the Gitea PR-review pipeline, the parallel-agent cross-repo refactor pattern, the acceptance-harness self-healing loop, the runbooks-from-diagnostic-sessions practice.
- **Keep output production-grade in regulated domains** — 24 years of DO-178C/V&V instincts applied to LLM output: what "done" really means, migration/i18n/routing completeness checklists, verification before declaration.

### Public / reproducible artifacts in this repo

- `claude-insights/stats.md` — full `/stats` snapshot with headline numbers, model breakdown, longest session, working-hour distribution.
- `claude-insights/insights.md` — per-project breakdown with session counts and date ranges.
- `claude-insights/insights-report-2026-04-21.{html,md,json}` — authoritative `/insights` report in three formats.
- `claude-insights/report.html` — narrative HTML insights report (earlier, March 2026).

### AI philosophy

Treat the LLM as a capable junior-to-mid engineer with infinite stamina and imperfect judgement. Set achievable, verifiable tasks. Decompose into context-window-sized chunks. Review completed work the same way you'd review a human's — more carefully at the edges (migrations, i18n wiring, routing registration) where LLMs under-specify. Published article on AI-augmented development on LinkedIn (featured post).

---

## Education

### National Research Nuclear University MEPhI
**MS Mathematics & Computer Science** | 1998 – 2006
*Mathematician, System Programmer*

Thesis: Optimization of avionics software verification — automatic test generation for airborne software with requirements represented as MATLAB models. Developed algorithm based on X-boolean logic. Evaluated effectiveness of the toolset.

### Additional Education
- **Software Architecture** — Yandex Practicum (2025)
- **Self-Driving Car Engineer Nanodegree** — Udacity (2021–2022)
- **Product Management & Analytics** — GoPractice (2020)
- **Product Management Intensive** — GeekBrains (2020)
- **Project Management** — Дизайн-бюро Артема Горбунова (2022)
- **Conflicts Resolution** — Soft Skills Lab (2020)

### MOOCs
- Introduction to Solid State Chemistry — MITx/edX (2012)
- Software as a Service — BerkeleyX/edX (2013)
- Introduction to Biology — MITx/edX (2013)

---

## Languages

- **Russian** — Native
- **English** — Fluent (professional working proficiency)
- **Spanish** — Basic

---

## Interests

Aviation, aerospace, self-driving cars, chemistry, bioinformatics, digital image processing, machine learning, Arduino/hardware projects, 3D modeling (Fusion 360)
