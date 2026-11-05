<h1 align="center">Hi, I'm Austin Creamer — "Apollo" 👋</h1>

<p align="center">
  <b>Senior Full-Stack & AI Engineer</b> · 7+ years shipping production software at <b>Zapier</b>, <b>Regions Bank</b>, <b>Shipt</b> and <b>Daxko</b>
</p>

<p align="center">
  <a href="https://apollo0229.github.io/portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-apollo0229.github.io-4f46e5?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/austin-creamer-8b2483260"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Austin%20Creamer-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:apollo000229@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-apollo000229%40gmail.com-db2777?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### What I do

- **Full stack, database to pixel:** React and TypeScript interfaces on top of Python, Node.js and C#/.NET services.
- **Distributed backends:** Kafka and Celery event pipelines, transactional outbox and hot/cold search over years of data.
- **Production AI:** LLM orchestration, RAG and validation layers that keep generated output safe to run.

### Experience

| Company | Role | Years | Highlight |
| --- | --- | --- | --- |
| **Zapier** | Senior Full-Stack Engineer | 2024‑26 | Natural-language → workflow engine with **91%** zero-shot success |
| **Regions Bank** | Senior Software Engineer / Full-Stack Team Lead | 2021‑24 | Core banking modernization, **−40%** mainframe dependency |
| **Shipt** | Full-Stack Engineer | 2020‑21 | Real-time fulfillment routing for up to **2.5M** active orders |
| **Daxko** | Software Engineer | 2019 | Spring Boot transaction workflows, **−20%** defects |

### 🛠️ Featured projects

#### Relay: webhooks in, nothing lost, processed once

An event pipeline built to survive crashes. Each webhook and its outbox message commit in one Postgres transaction, a Go relay moves them to Kafka, and Python workers apply every event exactly once, with delay-topic retries and a dead-letter topic. A live React dashboard follows it all over server-sent events.

- **Crash-tested:** the relay, worker, API and Kafka were killed with `SIGKILL` mid-load. 21,295 webhooks acknowledged, 21,295 processed once, none lost.
- **Load-tested:** 1,000 webhooks/s at 55 ms p95. The load test exposed a Postgres `NOTIFY` bottleneck; removing it lifted ingest 4.4×.

<p>
  <a href="https://github.com/Apollo0229/relay"><img alt="Source" src="https://img.shields.io/badge/Source-relay-24292f?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

Python · FastAPI · Go · Kafka · PostgreSQL · React · TypeScript · k6 · Docker · GitHub Actions

#### Flowsmith: plain English in, validated workflows out

Describe an automation and Flowsmith retrieves the right apps, plans a workflow with Claude (or an offline planner), and checks every step and data reference with a deterministic validator. Invalid plans go back to the model with structured hints for a correction pass.

<p>
  <a href="https://apollo0229.github.io/flowsmith/"><img alt="Live demo" src="https://img.shields.io/badge/Live%20demo-try%20it-4f46e5?style=for-the-badge"></a>
  <a href="https://github.com/Apollo0229/flowsmith"><img alt="Source" src="https://img.shields.io/badge/Source-flowsmith-24292f?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

TypeScript · React 19 · Vite · Claude Opus 5.5 (structured outputs) · BM25 retrieval · Vitest · GitHub Actions

### Featured case studies

- 🤖 **[Natural Language to Workflow Engine](https://apollo0229.github.io/portfolio/projects/natural-language-workflow-engine/)**: LLM router, vector retrieval and deterministic graph validation, **91%** zero-shot success.
- ⚡ **[Asynchronous Messaging Pipeline](https://apollo0229.github.io/portfolio/projects/async-messaging-pipeline/)**: Kafka, Celery and sidecar connection pooling, **−90%** broker connections.
- 🔎 **[Zap History & Audit Engine](https://apollo0229.github.io/portfolio/projects/zap-history-audit-engine/)**: hot/cold search streamed over SSE, **4.8 s → 320 ms**.
- 🎨 **[Visual Workflow Canvas](https://apollo0229.github.io/portfolio/projects/visual-workflow-canvas/)**: Canvas and Web Workers at **60 FPS** on 150+ steps.

All ten case studies, with architecture diagrams: **[apollo0229.github.io/portfolio](https://apollo0229.github.io/portfolio/)**

### On this account

- **[relay](https://github.com/Apollo0229/relay)**: crash-tested webhook pipeline with a transactional outbox, Kafka and exactly-once workers. Python, Go, React.
- **[flowsmith](https://github.com/Apollo0229/flowsmith)**: natural-language → validated workflow engine with a live demo. TypeScript, React, Claude.
- **[portfolio](https://github.com/Apollo0229/portfolio)** — my portfolio site: Next.js 16, React 19, Tailwind v4, Motion, static export to GitHub Pages.
- **[ai-customer-support-platform](https://github.com/Apollo0229/ai-customer-support-platform)** — *in progress:* AI customer support on Next.js, FastAPI, PostgreSQL and Redis.

### Toolbox

<p>
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
<img alt="React" src="https://img.shields.io/badge/React-149ECA?logo=react&logoColor=white">
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
<img alt="Django" src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white">
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white">
<img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white">
<img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white">
<img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white">
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
<img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?logo=redis&logoColor=white">
<img alt="Elasticsearch" src="https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white">
<img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
<img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white">
<img alt="LLMs / RAG" src="https://img.shields.io/badge/LLMs%20%2F%20RAG-7c3aed?logo=openai&logoColor=white">
</p>

### A note on this account

My original GitHub account, active since 2021, was compromised, so this account is a fresh start. Everything here is built new; my professional history is on my **[portfolio](https://apollo0229.github.io/portfolio/)** and **[LinkedIn](https://www.linkedin.com/in/austin-creamer-8b2483260)**.

---

<p align="center">Open to <b>Senior Full-Stack</b>, <b>Frontend</b>, <b>Backend</b> and <b>AI Engineer</b> roles · Birmingham, AL · Remote-friendly</p>
