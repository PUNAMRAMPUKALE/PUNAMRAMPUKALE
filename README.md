# Punam Pukale

**Backend Engineer · GenAI / LLM Engineer · Agentic AI**

I build backend systems and LLM-powered platforms — APIs, retrieval pipelines, multi-agent workflows, and computer-use automation — with production software engineering as the foundation.

[GitHub](https://github.com/PUNAMRAMPUKALE) · [LinkedIn](https://www.linkedin.com/in/punam-pukale-a8bb83ba/) · [Email](mailto:punampukale14@gmail.com)

---

## Professional introduction

I am a software engineer focused on **backend engineering** and **applied GenAI**. My public work shows how I design REST APIs, service boundaries, and data pipelines, then layer LLM orchestration on top: RAG with citations, multi-agent delivery workflows, evaluation backends, and guarded computer-use agents.

I am targeting roles such as **Backend Engineer**, **Software Engineer – Backend**, **GenAI Engineer**, **AI Platform Engineer**, and **Agentic AI Engineer**. I am not positioning myself as a frontend-only or full-stack generalist, and I am not positioning myself as an AI researcher disconnected from backend systems.

---

## Backend Engineering

I treat LLM features as services: typed contracts, modular APIs, persistence, auth, and deployable runtimes.

- REST APIs in **Python (FastAPI)** and **Java (Spring Boot / Hibernate / MySQL)**
- TypeScript backends with **Express**, **Prisma**, and **PostgreSQL**
- Service-oriented layout (auth + domain services), Docker packaging, and infra scaffolding
- Authentication and access control patterns (JWT/session-style auth, role-based access)
- Integrations with GitHub, Jira, Slack, and other HTTP APIs as first-class backend clients

---

## GenAI / Agentic AI

I build LLM applications that are grounded, orchestrated, and constrained — not prompt-only demos.

- **RAG platforms**: ingestion, embeddings, vector retrieval, citation-grounded answers, and shared retrievers across agents
- **Agentic systems**: multi-agent software-delivery pipelines (plan → retrieve context → patch → review → test → PR)
- **Computer-use agents**: observe → decide → act discovery, then deterministic replay with allowlists and human escalation
- **Evaluation**: experiment grids, response collection, local quality metrics, and streaming run progress
- **Safety**: retrieval-first reasoning, refusal when evidence is missing, and policy-gated irreversible actions

---

## What I Build

| Area | What it looks like in my work |
| --- | --- |
| AI platforms | Ingestion, retrieval, graph/knowledge layers, and recommendation/advice APIs on FastAPI |
| Agentic workflows | Multi-agent orchestration with tool-backed Git, Jira, GitHub, and Slack delivery |
| Grounded RAG | Shared vector stores + tool calls over structured records, with mandatory citations |
| Computer-use | LLM discovery of UI capabilities, versioned artifacts, deterministic replay, HITL handoff |
| Backend APIs | CRUD and experiment APIs, SSE streaming, Prisma/SQL persistence, Docker Compose data stores |
| Data / ML engineering | Transcript classification pipelines, MLflow experiment tracking, Docker/ECR/EC2 CI paths |

---

## Technical Skills

| | |
| --- | --- |
| Languages | Python, Java, TypeScript, JavaScript, SQL |
| Backend | FastAPI, Spring Boot, Express, REST API design, Pydantic / Zod validation |
| Data | PostgreSQL, MySQL, Redis, Prisma, SQLModel |
| GenAI | RAG, agents, tool calling, LangGraph, LangChain, CrewAI, prompt design, evaluation, guardrails |
| Cloud / runtime | Docker, AWS (EC2, ECR, GitHub Actions CI), Git |

---

## AI / GenAI Stack

| Capability | Tools used in public projects |
| --- | --- |
| LLM providers | OpenAI, Anthropic Claude, Google Gemini / Vertex AI, Groq, Ollama |
| Orchestration | LangGraph, LangChain, CrewAI, custom multi-agent pipelines |
| Retrieval | ChromaDB, Weaviate, PDF chunking / embeddings, repository graph retrieval |
| Knowledge / graphs | Neo4j, NetworkX (repo/dependency graphs) |
| Agents & tools | Tool calling over structured data, Git/GitHub/Jira/Slack tools, Playwright computer-use |
| Quality & safety | Citation enforcement, allowlist guardrails, escalation/handoff, local LLM quality metrics |
| Observability | Prometheus instrumentation (FastAPI), structured logs / evidence artifacts |

---

## Backend / Software Engineering Stack

| Layer | Stack |
| --- | --- |
| APIs | FastAPI, Express.js, Spring Boot, OpenAPI-style REST endpoints |
| Auth | JWT (`python-jose`), session/local auth, role-based access |
| Data | PostgreSQL, MySQL, Redis, Prisma ORM, Hibernate |
| Architecture | Modular services, multi-agent workflow state, Docker Compose for local/prod parity |
| Quality | pytest, typed models (Pydantic), Zod validation, GitHub Actions |

---

## Cloud / Infrastructure

| Area | Evidence in public work |
| --- | --- |
| Containers | Dockerfiles and Docker Compose (Postgres, Redis, Neo4j, app services) |
| AWS | ECR + EC2 deployment path with GitHub Actions (ML project) |
| CI/CD | GitHub Actions workflows; Prisma migrate/deploy for hosted backends |
| Observability | Prometheus / Grafana compose services; OpenTelemetry instrumentation on FastAPI |

---

## Featured Projects

Selected to show **agentic AI**, **RAG / AI platforms**, **computer-use**, **backend APIs**, and **ML / data engineering**. Repositories are unchanged; this is profile-only commentary.

### 1. [autonomous-software-agent](https://github.com/PUNAMRAMPUKALE/autonomous-software-agent)
**Agentic AI · LLM engineering · tool-using delivery pipeline**

Multi-agent software delivery system: Jira story selection, repository analysis/indexing, context retrieval, code generation, patch validation, review, tests, GitHub PR creation, Jira updates, and Slack notifications. Provider-agnostic LLM layer (OpenAI, Claude, Gemini, Ollama) with GitPython / PyGithub / Jira / Slack integrations.

`Python` · `multi-agent` · `tool calling` · `GitHub/Jira APIs`

### 2. [ng12-clinical-agent](https://github.com/PUNAMRAMPUKALE/ng12-clinical-agent)
**RAG · FastAPI · grounded LLM applications**

Clinical decision-support and conversational agent over NICE NG12 guidelines. Shared RAG pipeline (ChromaDB + Vertex AI embeddings/Gemini) reused by an assessor agent and a multi-turn chat agent. Tool calls over structured patient records, page-level citations, session memory, and explicit refusal when evidence is missing. LangGraph / LangChain-core on a FastAPI backend.

`FastAPI` · `LangGraph` · `ChromaDB` · `Vertex AI` · `guardrails`

### 3. [AI-Layer](https://github.com/PUNAMRAMPUKALE/AI-Layer)
**Computer-use · guardrails · deterministic replay**

LLM-driven agent discovers how to complete a goal in a mocked legacy UI, records a versioned capability artifact, then **replays without an LLM**. Includes allowlist policy, risky-action gating, structured error taxonomy, and human-in-the-loop escalation.

`Python` · `Playwright` · `Anthropic` · `Pydantic` · `pytest`

### 4. [finai](https://github.com/PUNAMRAMPUKALE/finai)
**AI platform · RAG · LangGraph / CrewAI**

Fintech analysis, recommendation, and profile-matching APIs: ingestion into a vector store, insight/recommend/crew-advice endpoints, and graph sync/query. Stack includes FastAPI, Weaviate, LangChain, LangGraph, CrewAI, Neo4j, PostgreSQL, Redis, JWT auth, Prometheus, Docker Compose, and AWS SDK (`boto3`).

`FastAPI` · `Weaviate` · `LangGraph` · `CrewAI` · `Postgres/Redis`

### 5. [llm-model-analyzer-backend-api](https://github.com/PUNAMRAMPUKALE/llm-model-analyzer-backend-api)
**Backend engineering · LLM evaluation**

TypeScript + Express API that runs prompt/parameter experiments against Groq, stores experiments/runs/responses/metrics in PostgreSQL via Prisma, streams progress with SSE, and exports JSON/CSV. Local metrics engine (completeness, coherence, redundancy, readability, overall quality). Docker Compose for local Postgres; Render-style deploy with `prisma migrate deploy`.

`TypeScript` · `Express` · `Prisma` · `PostgreSQL` · `SSE`

### 6. [REST_API](https://github.com/PUNAMRAMPUKALE/REST_API)
**Backend engineering · Java**

RESTful cloud-vendor API with **Java, Spring Boot, Hibernate, and MySQL** — CRUD-style backend service design with a Maven Spring Boot project layout.

`Java` · `Spring Boot` · `Hibernate` · `MySQL`

**Also relevant:** [Transcript-Intelligence](https://github.com/PUNAMRAMPUKALE/Transcript-Intelligence) (hybrid LLM + rules transcript categorization with an audit trail) · [notesphere](https://github.com/PUNAMRAMPUKALE/notesphere) (TypeScript auth/notes services + Docker) · [MachineLearningProjectWithMLFlow](https://github.com/PUNAMRAMPUKALE/MachineLearningProjectWithMLFlow) (MLflow tracking, Docker, AWS ECR/EC2 + GitHub Actions).

---

## GitHub / professional links

| | |
| --- | --- |
| GitHub | [github.com/PUNAMRAMPUKALE](https://github.com/PUNAMRAMPUKALE) |
| LinkedIn | [linkedin.com/in/punam-pukale-a8bb83ba](https://www.linkedin.com/in/punam-pukale-a8bb83ba/) |
| Email | [punampukale14@gmail.com](mailto:punampukale14@gmail.com) |
| Location | California, USA |

---

*Open to Backend, GenAI, AI Platform, and Agentic AI engineering roles.*
