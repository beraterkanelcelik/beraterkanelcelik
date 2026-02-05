# Berat Erkan Elçelik

**AI Engineer · M.Sc. Artificial Intelligence (University of Bremen)**

I build production AI systems — multi-agent orchestration, RAG pipelines, GPU-optimized inference, and real-time voice agents. I care about things that actually ship: measurable improvements, low latency, and clean observability.

Currently working as an AI Engineer at **PvFritz** (remote), building hierarchical multi-agent systems with LangGraph/MCP over a multi-tenant Django platform.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/beraterkanelcelik)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:elcelikberaterkan@gmail.com)
[![Website](https://img.shields.io/badge/Website-000?style=flat&logo=googlechrome&logoColor=white)](https://beraterkanelcelik.com)

---

## Work

**AI Engineer — PvFritz UG** · Mar 2025 – Present
- Hierarchical multi-agent system (Supervisor + 5 specialized agents) with LangGraph, MCP, and RBAC-based tenant isolation
- Hybrid RAG: pgvector semantic search + Qwen3 cross-encoder reranking → high-precision retrieval across isolated tenant data
- Multi-GPU inference (2× RTX 5070, Triton Inference Server, dynamic batching, OpenResty/Nginx) → **15–17 req/s, 40% latency reduction, 0% error rate over 27K+ requests**
- Observability with SigNoz: agent traces, GPU metrics, token usage, cost estimation

**Data Scientist — TAI (Turkish Aerospace Industries)** · Dec 2022 – Oct 2024
- RL agents for autonomous aircraft (F-16, SU-27, HURJET) — DDPG, PPO, TD3 from scratch with custom reward shaping
- Multi-agent dogfight training: 4 concurrent agents, adversarial self-play
- Anomaly detection on flight telemetry (Isolation Forest, LOF, LSTM Autoencoders)

---

## Projects

### [Agent Playground](https://github.com/beraterkanelcelik/Agent-Playground) — Multi-Agent AI Platform
LangGraph Functional API · supervisor pattern · async tool execution · human-in-the-loop checkpointing. RAG with pgvector, document processing with OCR, Langfuse observability. React/TypeScript frontend, Docker deployment.

### [RAG Reranker Evaluator](https://github.com/beraterkanelcelik/rag-reranker-evaluator) — Retrieval/Reranking Benchmark
Evaluation framework comparing embedding models (BGE, E5) and cross-encoder rerankers on Vectara Open RAGBench. Measures NDCG, MRR, Recall@K — quantifies retrieval quality vs. latency tradeoffs.

### [Real-Time Voice Customer Agent — Production Voice AI](https://github.com/beraterkanelcelik/customer-agent)
LangGraph + LiveKit + Twilio telephony. Supervisor-worker architecture with specialized agents for inventory lookup, appointment booking, FAQ handling, and human-in-the-loop escalation. Engineered audio pipeline with µ-law encoding and downsampling for telephony-grade quality.

### [TheUnichat](https://github.com/beraterkanelcelik) — Mobile App (React Native)
University student community app. Founded, designed, developed, launched on iOS/Android — **500+ users in the first week.**

---

## Tech

**Languages:** Python, JavaScript/TypeScript, SQL, C++, C

**AI/ML:** LangChain, LangGraph, MCP, PyTorch, HuggingFace Transformers, PPO/TD3/DDPG, Anomaly Detection

**RAG & Retrieval:** pgvector, Vector Search, Cross-Encoder Reranking

**Inference & Serving:** Triton Inference Server, vLLM, CUDA, Dynamic Batching

**Observability:** Langfuse, SigNoz, Custom Metrics Dashboards

**Infrastructure:** Docker, Kubernetes, AWS, Azure, PostgreSQL, MongoDB, Redis, Nginx

**Frontend:** React, React Native, TypeScript

---

## Education

**M.Sc. Artificial Intelligence & Intelligent Systems** — University of Bremen *(Oct 2024 – Present)*

**B.Sc. Computer Engineering** — Ankara University *(GPA: 3.76/4)*

---

## Stats

<p align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app/?user=beraterkanelcelik&theme=transparent&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="GitHub Streak" />
</p>
