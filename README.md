<h1 align="center">Diya Hussein</h1>
<h3 align="center">AI Infrastructure & Systems Engineer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Timi%C8%99oara%2C%20Romania-888" alt="Location">
  <img src="https://img.shields.io/badge/Focus-AI%20Infrastructure%20%7C%20ML%20Systems%20%7C%20Real--Time%20Data-blue" alt="Focus">
  <img src="https://img.shields.io/badge/Languages-Arabic%20%7C%20English%20%7C%20German%20B2%20%7C%20Romanian%20%7C%20Mandarin%20(in%20progress)-green" alt="Languages">
</p>

---

I build the infrastructure that makes AI work at scale — real-time inference pipelines, event-streaming architectures, and high-performance ML serving systems.

My work bridges **machine learning** and **low-level systems engineering**. I care about what happens between the model and the metal: ONNX quantization, kernel-bypass I/O, stream processing at 1000+ msg/sec, and inference servers that don't crash under load.

### What I'm Building

| Project | Description | Stack |
|---------|-------------|-------|
| [EdgeSight](https://github.com/DiyaHussein/edgesight) | Real-time edge AI pipeline — YOLOv8 + ONNX quantization + Grafana monitoring. 15ms CPU inference. | Python, PyTorch, ONNX, FastAPI, Docker |
| [KafkaLens](https://github.com/DiyaHussein/kafkalens) | Kafka stream processing with sliding-window anomaly detection. Full pipeline: producer → broker → ML consumer → Grafana. | Python, Kafka, scikit-learn, PostgreSQL |
| [rs-mlserve](https://github.com/DiyaHussein/rs-mlserve) | Rust ONNX inference server over gRPC with native Python client (PyO3). 3.2x faster than Python, survives SIGKILL. | Rust, PyO3, gRPC, ONNX Runtime |
| [rust-quant-engine](https://github.com/DiyaHussein/rust-quant-engine) | Tick-level backtesting engine with limit order book simulation and Sharpe/Sortino metrics. | Rust, PyO3 |
| [tcp-proxy-rs](https://github.com/DiyaHussein/tcp-proxy-rs) | Asynchronous L4 proxy leveraging io_uring for kernel-bypass I/O. Sub-50us latency. | Rust, tokio, io_uring |

### Stack

**AI / ML**

<p>
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&style=flat-square">
  <img src="https://img.shields.io/badge/-ONNX-005CED?logo=onnx&style=flat-square">
  <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&style=flat-square">
  <img src="https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikit-learn&style=flat-square">
  <img src="https://img.shields.io/badge/-HuggingFace-FFD21E?logo=huggingface&style=flat-square">
  <img src="https://img.shields.io/badge/-LangChain-1C3C3C?logo=langchain&style=flat-square">
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

### What I Know

- **Computer Vision Pipelines** — real-time object detection, ONNX quantization, edge deployment, model benchmarking
- **Stream Processing** — Kafka event-streaming architectures, sliding-window ML, anomaly detection at scale
- **ML Infrastructure** — model serving (Rust/gRPC), MLOps tooling, Prometheus/Grafana observability
- **Systems Programming** — kernel-bypass networking (io_uring), lock-free data structures, eBPF tracing
- **Quantitative Systems** — order book simulation, backtesting engines, FIX protocol

### Open Source

- Apache Kafka contributor
- TiDB contributor (CNCF graduated)

### Contact

Timișoara, Romania · diya.minamoto@gmail.com
