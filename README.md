<h1 align="center">Diya Hussein</h1>
<h3 align="center">AI Infrastructure & Systems Engineer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Timi%C8%99oara%2C%20Romania-888" alt="Location">
  <img src="https://img.shields.io/badge/Focus-AI%20Agents%20%7C%20ML%20Systems%20%7C%20Real--Time%20Data-blue" alt="Focus">
  <img src="https://img.shields.io/badge/Languages-Arabic%20%7C%20English%20%7C%20German%20B2%20%7C%20Romanian%20%7C%20Mandarin%20(in%20progress)-green" alt="Languages">
</p>

---

I build the infrastructure that makes AI work at scale — real-time inference pipelines, event-streaming architectures, and high-performance ML serving systems.

My work bridges **machine learning** and **low-level systems engineering**. I care about what happens between the model and the metal: ONNX quantization, kernel-bypass I/O, stream processing at 1000+ msg/sec, and inference servers that don't crash under load. Lately that same interest has moved up the stack — into agents that run locally, agents that speak two languages, and the question of whether you can trust the packages an agent pulls in.

## Agents & Applied LLM Systems

Trust, deployment, and the unglamorous parts of making language models useful.

| Project | Description | Stack |
|---------|-------------|-------|
| [sigil](https://github.com/DiyaHussein/sigil) | A trust registry for MCP servers and agents. Answers what a package **gained** since the version you approved — version-diffing that catches rug pulls, every finding backed by file, line and source. | Python, FastAPI, static analysis |
| [sanad](https://github.com/DiyaHussein/sanad) | Multi-tenant AI receptionist platform — bilingual AR/EN booking, photo-to-quote estimating, per-client config as YAML. One codebase, many businesses. | Python, FastAPI, DeepSeek, vision |
| [drex](https://github.com/DiyaHussein/drex) | Dark, unfiltered DeepSeek terminal agent with its own file/terminal/web tool registry. | Python, DeepSeek, tool-use |
| [sentinel](https://github.com/DiyaHussein/sentinel) | Fully offline terminal agent on Ollama — no cloud, no API key. Cinematic boot, `/learn` memory loop, `/read` career reading. | Python, Ollama, local LLM |
| [yone](https://github.com/DiyaHussein/yone) | Spirit Blossom terminal agent that teaches Python in Romanian — tiered curriculum, hints over answers, persistent student memory. | Python, DeepSeek, education |
| [study-companion](https://github.com/DiyaHussein/study-companion) | Local Ollama study agent — drop PDFs in, get summaries, quizzes, study plans, RO/EN translation and exam-question prediction. | JavaScript, FastAPI, Ollama |
| [deepseek-lead-bots](https://github.com/DiyaHussein/deepseek-lead-bots) | n8n + DeepSeek receptionist and lead-qualification agents — bilingual AR/EN intent, generation and slot-filling in one strict-JSON call. | n8n, DeepSeek, WhatsApp |
| [hermes-skills](https://github.com/DiyaHussein/hermes-skills) | Nine drop-in e-commerce and dropshipping skill packs for the Hermes Agent. | Agent skills, Shopify |

## Systems & Performance

Latency, throughput, and getting close to the metal.

| Project | Description | Stack |
|---------|-------------|-------|
| [lob-replay](https://github.com/DiyaHussein/lob-replay) | Sub-millisecond L2 order book reconstructor — Binance, OKX, Bybit tick streams → Apache Arrow IPC. 1M+ events/sec. | Rust, Apache Arrow, criterion |
| [tcp-proxy-rs](https://github.com/DiyaHussein/tcp-proxy-rs) | Ultra-low-latency async L4 TCP proxy with io_uring kernel bypass. Sub-50µs added latency. | Rust, tokio, io_uring |
| [rust-quant-engine](https://github.com/DiyaHussein/rust-quant-engine) | High-performance event-driven backtesting engine with limit order book simulation and Sharpe/Sortino metrics. | Rust, PyO3 |
| [transformer-jax](https://github.com/DiyaHussein/transformer-jax) | GPT-style decoder from scratch in JAX — multi-head attention, flash attention, WikiText-2 training. | Python, JAX, dm-haiku, optax |
| [edgesight](https://github.com/DiyaHussein/edgesight) | Real-time edge AI pipeline — YOLOv8 + ONNX quantization + FastAPI + Grafana monitoring. 35ms CPU inference. | Python, PyTorch, ONNX, Docker |

## Stack

**AI / ML**

<p>
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&style=flat-square">
  <img src="https://img.shields.io/badge/-ONNX-005CED?logo=onnx&style=flat-square">
  <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&style=flat-square">
  <img src="https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikit-learn&style=flat-square">
  <img src="https://img.shields.io/badge/-HuggingFace-FFD21E?logo=huggingface&style=flat-square">
  <img src="https://img.shields.io/badge/-LangChain-1C3C3C?logo=langchain&style=flat-square">
  <img src="https://img.shields.io/badge/-Ollama-000?logo=ollama&style=flat-square">
</p>

**Data & Streaming**

<p>
  <img src="https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&style=flat-square">
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&style=flat-square">
  <img src="https://img.shields.io/badge/-Redis-DC382D?logo=redis&style=flat-square">
</p>

**Infrastructure & DevOps**

<p>
  <img src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&style=flat-square">
  <img src="https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&style=flat-square">
  <img src="https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&style=flat-square">
  <img src="https://img.shields.io/badge/-Grafana-F46800?logo=grafana&style=flat-square">
  <img src="https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&style=flat-square">
  <img src="https://img.shields.io/badge/-GitHub_Actions-2088FF?logo=githubactions&style=flat-square">
</p>

**Systems**

<p>
  <img src="https://img.shields.io/badge/-Rust-000?logo=rust&style=flat-square">
  <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&style=flat-square">
  <img src="https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&style=flat-square">
  <img src="https://img.shields.io/badge/-JAX-4285F4?logo=jax&style=flat-square">
  <img src="https://img.shields.io/badge/-io__uring-000?logo=linux&style=flat-square">
  <img src="https://img.shields.io/badge/-eBPF-000?logo=linux&style=flat-square">
</p>

## What I Know

- **Agent Systems** — tool-use registries, MCP server security, supply-chain diffing, multi-tenant agent deployment
- **Applied LLM** — bilingual (AR/EN/RO) intent and slot-filling, strict-JSON single-call pipelines, offline/local inference
- **Computer Vision Pipelines** — real-time object detection, ONNX quantization, edge deployment, model benchmarking
- **Stream Processing** — Kafka event-streaming architectures, sliding-window ML, anomaly detection at scale
- **ML Infrastructure** — model serving (Rust/gRPC), MLOps tooling, Prometheus/Grafana observability
- **Systems Programming** — kernel-bypass networking (io_uring), lock-free data structures, eBPF tracing
- **Quantitative Systems** — order book simulation, backtesting engines, FIX protocol

## Open Source

- All projects MIT licensed. Building infrastructure in public.
- Exploring contribution opportunities in Kafka, JAX, and TiDB ecosystems.

## Contact

Timișoara, Romania · diya.minamoto@gmail.com
