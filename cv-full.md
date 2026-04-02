# Sergey Subbotin

**Technical Lead**

Belgrade, Serbia | ssubbotin@gmail.com
[linkedin.com/in/ssubbotin](https://linkedin.com/in/ssubbotin) | [github.com/ssubbotin](https://github.com/ssubbotin) | [medium.com/@sergeysubbotin](https://medium.com/@sergeysubbotin)

---

## Summary

Technical Lead with 22+ years of experience across safety-critical avionics, large-scale distributed infrastructure, and aerospace radar systems. Led cross-functional teams of up to 10 engineers spanning development, QA, and DevOps. Career progression from Engineer through Scrum Master and Team Lead to hands-on Technical Lead -- always staying close to the code while scaling impact through people and processes.

Rare combination of safety-critical domain expertise (DO-178C, FAA certification, 30+ avionics projects) and big-tech infrastructure experience at scale (millions of RPS, thousands of servers). Proven ability to rescue stalled projects, build teams from scratch, design system architecture, and deliver on time. Integrates AI-augmented workflows into daily engineering practice -- from LLM-powered code review to production MCP tooling -- across multinational teams in Russia, Argentina, and Serbia.

---

## Technical Skills

### Languages
**Primary:** Python, Go, C/C++, TypeScript
**Proficient:** SQL, Protobuf, Java

### Infrastructure & DevOps
- **Containers & Orchestration:** Docker, Docker Compose, Docker Swarm
- **Service Mesh & Load Balancing:** Nginx (L3/L7), ZooKeeper, RabbitMQ, gRPC
- **Databases:** MongoDB, Redis, PostgreSQL, MySQL, Elasticsearch, SQLite
- **CI/CD:** GitHub Actions, Gitea Actions, Jenkins, GitLab CI, Bamboo
- **Cloud:** AWS (EC2, S3, spot fleets), Yandex Cloud, Google App Engine

### Monitoring & Observability
Grafana, Prometheus, ELK Stack (Elasticsearch, Logstash, Kibana), OpenTelemetry

### Frameworks & Tools
React, Node.js, Svelte, gRPC, TVM, Proxy Protocol, LLVM/Clang, IBM DOORS, IBM ClearCase, Hex-Rays IDA Pro, Matlab, Jinja2

### AI Tooling
MCP servers, LLM-driven code review pipelines, multi-agent orchestration, full-stack project bootstrapping (Claude Code, GitHub Copilot)

### Practices
Agile/Scrum (10 years, 3 as Scrum Master), Code Review, CI/CD, DO-178B/C Verification & Validation, Pair Programming, Mentoring

---

## Experience

### Team Lead -- AeroNAV (Navigator LLC)
**Jan 2025 -- Present** | Remote (Contract)
*Airport Meteorological Radar System (RLMKX) -- control and monitoring system for airport radar complex*

Lead a team of 8 (3 backend developers, 1 frontend developer, 1 UX/UI designer, 1 analyst, 1 domain expert) as both Project Manager and Technical Lead.

**Key contributions:**
- Architected the system across 11 repositories; technology stack includes C++, nesC, TypeScript, Python, CMake, and Docker
- Established CI/CD pipelines (Gitea Actions), code review process, and DevOps infrastructure from scratch, driving 2,900+ commits and 605+ pull requests
- Implemented LLM-powered code review as the standard PR workflow across all 11 repositories; deployed multi-agent orchestration (5 parallel agents) for cross-repo C++ static analysis and style enforcement
- Bootstrapped new services from zero to production using AI-augmented development workflows, reducing initial project setup time
- Manage hiring, performance reviews, sprint planning, and cross-functional coordination with hardware and analytics teams
- Integrated with Redmine issue tracker; designed development workflows and team onboarding procedures

---

### Software Developer -- Yandex
**May 2023 -- Present** | Belgrade, Serbia (Hybrid)
*L3/L7 load balancing control plane orchestrating traffic for millions of requests per second to internal and external Yandex services*

**Contribution volume (Arcadia monorepo):**
- 366 merged PRs, 446 commits, 122,000+ lines added, 2,787 files changed
- 869 PRs reviewed from teammates
- 165+ new features implemented across balancer configuration, L7 routing, DNS, ZooKeeper state management, and certificate management
- Stack: Python, Jinja2, YAML, Lua, Protobuf, Go

**L7 Balancer Migration to Deploy Platform**
- Designed migration plan and built migration tooling; defended design at cross-team strategy session
- Migrated 750+ L7 balancers to Deploy (270 production), including complex multi-datacenter setups
- Adopted early by Maps, E-commerce, and RideTech teams as the standard migration path

**Infrastructure at Scale**
- Migrated 7,000+ balancers to new Unified Agent versions across 5 datacenters (SAS, VLA, MAN, KLG, MSK)
- Introduced TVM authentication across 358+ balancers, strengthening security posture
- Implemented OpenTelemetry distributed tracing and gRPC support (100+ upstreams)
- Built automated export pipeline for 1.5M+ entities to internal developer platform (IDP)
- Drove 46 balancer configuration changes and 40 deployment/release cycles

**Performance & Reliability**
- Accelerated API response time by 30% through caching optimization, SAGA pattern, and ZooKeeper-to-cache migration
- Eliminated 2,000+ flaky tests; reduced test suite execution from 30 to 20 minutes using mongomock
- Implemented matcher map feature, adopted by 50+ namespaces for improved request routing UX
- Added Proxy Protocol support, .com domain WebAuth, and PCI DSS cipher presets
- Resolved 150+ critical bugs in BALANCERSUPPORT queue; closed 101 tasks in a single review cycle
- Created alerting templates for E-commerce and RideTech; migrated 3,710 namespaces

**Innovation & Tooling**
- Built production MCP server with 20+ tools enabling natural-language management of balancers, namespaces, and certificates through LLM integration
- Created SAT solver prototype for go.mod dependency resolution in monorepo (adopted into standard tooling)
- Developed auto-changelog generation for balancer macros, driving 5,000+ balancer upgrades
- Built state machine visualization scripts generating Mermaid diagrams for system documentation

**Documentation & Mentoring**
- Reviewed and improved 30+ documentation PRs in collaboration with technical writers
- Mentored 5+ bootcamp engineers through onboarding and project ramp-up
- Led daily standups and coordinated releases during team lead's absence
- Published internal blog posts on debugging techniques, log export, and test acceleration
- Authored LinkedIn article on integrating AI-augmented development into infrastructure engineering workflows

**Colleague feedback:**
> "Mission critical feature... everything was done in tight deadlines." -- Roman Volchanskiy (TVM authentication)
> "Matcher Map is just an excellent thing, greatly improving UX." -- Evgeny Kharrasov (Maps team)
> "The migration mechanism is awesome, will save many man-hours." -- Vadim Mazaev (Deploy migration)
> "Results of acceleration are clearly visible, very cool result!" -- Polina Lukina (API performance)

---

### Team Lead -- International Aero Navigation Systems Concern (IANS), JSC
**Mar 2021 -- May 2023** (2 yrs 3 mos) | Moscow
*Aeronautical technologies and R&D for civil aviation*

Led project management, technical architecture, and DevOps for two aerospace projects:

**Meteorological Airport Information System** (delivered on schedule)
- Rescued a stalled project that had only 1 junior frontend developer; grew the team to 5 engineers by recruiting from adjacent projects
- Selected technology stack (JavaScript, React, Python, MongoDB), designed system architecture, and established linting, unit testing, and CI/CD from scratch
- Delivered the system on schedule despite inheriting significant technical debt

**RUTM1 -- Unmanned Aircraft Traffic Management (UTM) Web Service**
- Hired and built a 6-person team (backend, frontend, QA, UX/UI) through full recruitment cycle
- Selected technology stack (TypeScript, React, Go, MongoDB, RabbitMQ) and designed microservice architecture
- Established the complete development process including branching strategy, code review, and deployment pipelines

**Organizational improvements:**
- Introduced Agile/Scrum framework with sprint-based delivery to the engineering organization
- Implemented the company's first formal performance review process
- Set up monitoring and infrastructure: ELK stack, Grafana/Prometheus/Alertmanager, Docker Swarm

---

### Senior Developer -- Avature
**Jun 2017 -- Nov 2020** (3 yrs 6 mos) | Buenos Aires, Argentina
*Human Capital Management SaaS platform -- privately held, enterprise-grade HR software*

Optimized and evolved an in-house test automation system processing 2 million tests daily on Amazon AWS using 2,000 instances under high load.

**Key achievements:**
- Doubled the number of tests executed per machine-hour through optimization of test scheduling and resource allocation
- Reduced cloud infrastructure costs by over 50% through spot fleet optimization and improved instance utilization
- Built responsive, auto-updating UI with an extensible template system, reducing content delivery latency for end users
- Designed and implemented Ubuntu and Windows server spot fleet provisioning from scratch

**Recommendations:**
> "When facing any problem he goes deep to understand its root, in order to come up with a great solution from both technical and functional point of view. Super dedicated to his job, he has really made a difference with great impact." -- Guillermo Sabbatella, Director of Engineering

> "Sergey is great at both generating new ideas and implementing new things. He is used to create software that exceeds users expectations and he does it by ticking all the boxes good software is supposed to have on quality, maintainability and security." -- Juanleon Lahoz, VP of DevOps

---

### Lead Software Engineer -- DC BARS Inc.
**Feb 2003 -- Mar 2017** (14 yrs 2 mos) | Moscow
*Avionics software development, Verification & Validation, and DO-178 certification support*

Progressed from software engineer to lead over 14 years, contributing to 30+ avionics projects and 10+ aircraft certified by FAA.

**Honeywell & Rockwell Collins Avionics Programs** (Feb 2003 -- Apr 2010, 7 years)
- Led verification teams of 2-15 engineers for Honeywell Primus Epic Display Systems (5 years) and Rockwell Collins Pro Line Fusion Avionics (2 years)
- Performed requirement-based testing, structural coverage analysis, system integration testing, and formal inspections
- Delivered on-site work at both Honeywell (4 months) and Rockwell Collins (7 months); trained and onboarded the Moscow-based team

**Certivision -- Requirements & Change Management System** (Apr 2010 -- Jul 2013, 3 years)
- Architected and developed an Eclipse-based system integrating version management with change management and formal inspection support (DO-178B compliance)
- Served as Scrum Master for an agile team of 9 engineers
- Technologies: Java, Eclipse plugin framework, C++

**DO-178C Qualified Toolset** (Jul 2013 -- Nov 2016, 3 years)
- Initiated and sold the project concept to management; designed complete system architecture
- Built a qualified toolset for DO-178C Level A certification: structural coverage collection, worst-case execution time (WCET) estimation, heap/stack usage analysis, and control flow analysis
- Core technology: LLVM/Clang compiler frontend (C++, STL)

**Test Automation**
- Conceived, proposed, and implemented tooling that automated routine test development, saving 30%+ engineering time for targeted requirement categories

**Recommendation:**
> "He has a very short learning curve and in almost no time you will have a solution or recommendations -- he is equally capable of seeing the whole picture and dig deep into details of all tasks assigned to him. He perfectly works autonomously and as a part of a big team." -- Alexander Bogdanov, Director of Business Development

---

### Software Developer -- RUSIST Security
**Apr 2001 -- Feb 2003** (1 yr 11 mos) | Moscow
*CCTV video monitoring and surveillance systems*

- Developed BT878 chipset video capture drivers (C++, Windows DDK, DirectShow) achieving 25 fps capture rate
- Built SDK enabling integration with third-party surveillance systems
- Improved network throughput and overall system stability for distributed CCTV deployments

---

## Open Source Contributions

**flash-moe (2026)**
CUDA port of a pure C/Metal inference engine that runs Qwen3.5-397B-A17B (397B parameter MoE model) on consumer hardware. Hand-written CUDA kernels, VRAM expert caching, GDS support. [Article: Running 397B on a single RTX 4090](https://gist.github.com/ssubbotin/e778f97ebf1f76b8fd423c0bc3961a1a).

**libfprint (2026)**
New driver for FPC Disum USB fingerprint sensors (FPC1022). TLS-PSK encrypted USB protocol, SIFT-based matching for small-area sensors. [Merge request](https://gitlab.freedesktop.org/libfprint/libfprint/-/merge_requests/570).

**LLVM / clang-format (2026)**
Merged upstream PR: [Add per-operator granularity for BreakBinaryOperations](https://github.com/llvm/llvm-project/pull/181051)

**Personal Projects**
- **BORODA** -- Requirements management system for DO-178C/KT-178C certification (TypeScript)
- **cudascope** -- Self-hosted NVIDIA GPU monitoring with real-time dashboards (Go)
- **gost-r-54084-2010** -- Atmospheric boundary layer models for aerospace applications (Python)
- **redis-ui** -- Web-based management interface for Redis (JavaScript)
- **zookeeper-ui** -- Web UI for Apache ZooKeeper with protobuf message decoding (JavaScript)

---

## Education

### National Research Nuclear University MEPhI
**MS Mathematics & Computer Science** | 1998 -- 2006
*Mathematician, System Programmer*

Thesis: Optimization of avionics software verification -- automatic test generation for airborne software with requirements represented as MATLAB models. Developed algorithm based on X-boolean logic.

### Professional Development
- **Software Architecture** -- Yandex Practicum (2025)
- **Self-Driving Car Engineer Nanodegree** -- Udacity (2021--2022)
- **Product Management & Analytics** -- GoPractice (2020)
- **Product Management Intensive** -- GeekBrains (2020)
- **Project Management** -- Bureau of Artem Gorbunov (2022)
- **Conflict Resolution** -- Soft Skills Lab (2020)

---

## Languages

- **Russian** -- Native
- **English** -- Fluent (professional working proficiency)
- **Spanish** -- Basic
