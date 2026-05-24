# Preetham Reddy

**AI Engineer · 6 years building production systems at the intersection of LLMs, backend engineering, and ML infrastructure**

Open to Senior AI Engineering, GenAI Engineering, and ML Engineering roles.

---

## About

I build end-to-end AI systems — from data ingestion and model fine-tuning to production APIs and observability. Over six years I've worked across backend engineering, applied ML, and the infrastructure that keeps models reliable in production.

My focus areas right now: retrieval-augmented generation, multi-agent systems, LLM fine-tuning (LoRA/QLoRA), and scalable ML serving.

I care about systems that are observable, reproducible, and maintainable — not just systems that demo well.

---

## Stack

**LLM & GenAI**
LangChain · LlamaIndex · OpenAI API · Anthropic API · Hugging Face Transformers · PEFT / LoRA / QLoRA · vLLM · Ollama

**Retrieval & Vector Search**
FAISS · Pinecone · Weaviate · ChromaDB · pgvector · Qdrant

**ML Frameworks**
PyTorch · scikit-learn · XGBoost · Sentence-Transformers

**Backend & APIs**
Python · FastAPI · PostgreSQL · Redis · Celery · SQLAlchemy

**MLOps & Infra**
Docker · Kubernetes · GitHub Actions · MLflow · Weights & Biases · Prometheus · Grafana

**Cloud**
AWS (SageMaker, Lambda, S3, ECR) · GCP (Vertex AI, Cloud Run) · Azure (OpenAI Service)

---

## What I'm Working On

- Multi-agent orchestration framework with LangGraph for autonomous task decomposition
- Production RAG pipeline with hybrid search (dense + BM25 re-ranking) and hallucination detection
- Fine-tuning Mistral-7B on domain-specific QA using QLoRA + DPO

---

## Selected Projects

**enterprise-rag-pipeline**
Production RAG system with adaptive chunking, hybrid retrieval, query rewriting, and Ragas-based eval harness. Handles 10k+ document corpora. FastAPI backend, Dockerized, CI/CD via GitHub Actions.
`Python · LangChain · FAISS · FastAPI · Docker · MLflow`

**llm-finetuning-toolkit**
End-to-end fine-tuning pipeline for instruction-tuned LLMs using LoRA and QLoRA on consumer hardware. Includes dataset prep, training, quantization, evaluation (MT-Bench style), and Hugging Face Hub push.
`Python · PyTorch · PEFT · Transformers · BitsAndBytes · W&B`

**agent-workflow-engine**
Multi-agent system built with LangGraph. Supports tool-calling agents, memory management, parallel execution, and automatic error recovery. Deployable as a REST API.
`Python · LangGraph · LangChain · FastAPI · Redis`

**mlops-serving-stack**
ML model serving infrastructure: containerized FastAPI inference server with request batching, model versioning, Prometheus metrics, and autoscaling via Kubernetes HPA.
`Python · FastAPI · Docker · Kubernetes · Prometheus · Grafana`

**document-intelligence-api**
Document parsing and extraction service using vision-language models (LLaVA, ColPali). Handles PDFs, images, and mixed-format documents. Structured JSON output with confidence scoring.
`Python · FastAPI · LLaVA · PyMuPDF · Tesseract · PostgreSQL`

---

## Experience Snapshot

- Designed and shipped RAG systems that serve production traffic — not just notebooks
- Built LLM evaluation frameworks (automated + human-in-the-loop) to track quality regressions
- Operated ML workloads on Kubernetes: rolling deploys, canary testing, resource quotas
- Worked with SyncPad, API rate-guard, k8s-workload-scaler, and custom alerting infrastructure
- Contributed to backend systems before moving full-time into ML Engineering

---

## Engineering Principles

Production-first. A model that works in a notebook is not a model that works.
Observable by default. Every inference call should be traceable and measurable.
Skeptical of complexity. Use the simplest architecture that actually solves the problem.
Documentation as a first-class artifact. If it isn't documented, it doesn't exist.

---

## Contact

- LinkedIn: [linkedin.com/in/preetham-reddy](https://linkedin.com/in/preetham-reddy)
- Open to work: Senior AI Engineer · GenAI Engineer · ML Engineer · Backend AI Engineer
