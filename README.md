# Hi, I'm Sergey Subbotin

**Staff Engineer @ Avature** based in Madrid, Spain

24+ years building software — from safety-critical avionics certified by the FAA to cloud infrastructure handling millions of RPS at Yandex. Focused on **AI-augmented engineering**: shipping at LLM-accelerated pace while keeping output production-grade.

## Claude Code, by the numbers (2026-01 → 11)

- **1,136 sessions, 872K messages, 414K tool calls, 104 B tokens, 244 active days**
- Mostly Claude Opus (~84% of tokens: Opus 4.5 → 5.5); also Sonnet, Fable and Haiku for subagents
- Dozens of projects: an OS kernel, video meetings, GPU inference engines, Kaggle campaigns, radar software, tooling

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
- **Kaggle: 2 silver medals** — [ROGII Wellbore Geology Prediction](https://www.kaggle.com/competitions/rogii-wellbore-geology-prediction) (113th of 6,125 teams) and [RSNA Knee Abnormality Detection](https://www.kaggle.com/competitions/rsna-knee-abnormality-detection) (6,299 teams); solo, with research campaigns run through Claude Code ([skills](https://github.com/ssubbotin/kaggle-research-skills))

## Open source

- [**stafeto**](https://github.com/stafeto/stafeto) — a POSIX operating system on its own capability microkernel, written in Rust for AArch64. ~210 KiB kernel with 38 system calls, bounded interrupt-off time enforced in CI, fixed-priority and sporadic-server scheduling, up to 8 CPUs; drivers and services run as isolated user processes. All 1,035 POSIX.1-2024 interfaces present; runs bash, nano, htop, nginx, curl and Dropbear SSH on QEMU, Apple silicon (HVF / Virtualization.framework) and AWS EC2 Graviton. ~4,000 commits, release v0.6.0. [Site](https://stafeto.github.io).
- [**kunveno**](https://github.com/ssubbotin/kunveno) — self-hosted video meetings for private networks: Go SFU server + Svelte web client, no accounts, no STUN/TURN, no third-party services. Cameras, screen sharing, in-browser virtual backgrounds and noise suppression, ICE-over-TCP fallback, Prometheus metrics; add-ons for speech-recognised meeting notes, MP4 recording and a voice bot that runs the daily stand-up. AGPL-3.0, release v0.10.0.
- [**windlass**](https://github.com/ssubbotin/windlass) — single-GPU CUDA inference engine for mixture-of-experts models larger than VRAM: dense weights resident on the card, routed experts streamed from NVMe through an LRU cache. Runs GLM-5.2 (753B total / 39B active) on one 96 GB card. Pure C/CUDA, no dependencies.
- [**flash-moe**](https://github.com/ssubbotin/flash-moe) — multi-vendor GPU port of the Metal-only inference engine that runs Qwen3.5-397B-A17B (397B-param MoE) on consumer hardware. **233 commits across four branches**: CUDA (61), ROCm (46), AMD APU / Strix Halo (73, incl. dp4a + undocumented hipMalloc discoveries), and MI300 optimization (53, aotriton flash-attn + FLA fused recurrent). [Article: Running 397B on a single RTX 4090](https://gist.github.com/ssubbotin/e778f97ebf1f76b8fd423c0bc3961a1a).
- [**libfprint**](https://gitlab.freedesktop.org/libfprint/libfprint/-/merge_requests/570) — new driver for FPC Disum USB fingerprint sensors (FPC1022). TLS-PSK encrypted USB protocol, SIFT-based matching for small-area sensors.
- [**LLVM/clang-format**](https://github.com/llvm/llvm-project/pull/181051) — merged PR: per-operator granularity for BreakBinaryOperations
- [**kaggle-research-skills**](https://github.com/ssubbotin/kaggle-research-skills) — Claude Code skills for disciplined open-ended research, distilled from ML competition campaigns: TRIZ-based researcher, invention council, research loop, LLM council, Kaggle campaign playbook
- [**dossh**](https://github.com/ssubbotin/dossh) — SSH into a real-mode DOS PC: a TSR SSH server that mirrors the VGA text screen and injects the keyboard over TCP/IP (C, v1.0)
- [**slim-s3**](https://github.com/ssubbotin/slim-s3) — slim S3 client for C++17: libcurl only, own SigV4 signing, timeouts on by default
- [**cudascope**](https://github.com/ssubbotin/cudascope) — self-hosted NVIDIA GPU monitoring (Go)
- [**redis-ui**](https://github.com/ssubbotin/redis-ui) — modern web UI for Redis
- [**zookeeper-ui**](https://github.com/ssubbotin/zookeeper-ui) — web UI for Apache ZooKeeper with protobuf support
- [**gost-r-54084-2010**](https://github.com/ssubbotin/gost-r-54084-2010) — atmospheric boundary layer models for aerospace (Python)

## Links

- [CV (short)](cv-short.md) | [CV (full)](cv-full.md)
- [LinkedIn](https://linkedin.com/in/ssubbotin)
- [Medium](https://medium.com/@sergeysubbotin)
