<p align="center">
  <img src="./assets/himanshu-ai-workbench.svg" alt="Himanshu AI Workbench" width="100%" />
</p>

<h1 align="center">Himanshu Kumar</h1>

<p align="center">
  <strong>Full Stack AI Developer</strong><br />
  FastAPI | Next.js | AI Agents | Voice Systems | Data Products
</p>

<p align="center">
  <a href="mailto:jhahimanshu653@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/himanshu748"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/himanshu748?tab=repositories"><img src="https://img.shields.io/badge/All%20Repos-181717?style=for-the-badge&logo=github&logoColor=white" alt="All Repositories" /></a>
</p>

<p align="center">
  Building practical AI systems with reliable APIs, clean UX, and production-minded engineering.
</p>

---

## How I Build

| Area | Engineering focus |
| --- | --- |
| Agent systems | Tool-calling reliability, constrained outputs, failure-safe behavior |
| Product delivery | FastAPI backend + modern React/Next.js frontend |
| Voice and realtime | Low-latency STT -> model -> TTS loops |
| Data projects | Clear storytelling with reproducible analysis pipelines |
| OSS workflow | High-velocity iteration across active upstream forks |

---

## Best Projects (Live Snapshot: 2026-02-22)

Selection logic: recency of updates, technical depth, and direct end-user usefulness.

| Rank | Project | Type | Updated | Why it stands out |
| --- | --- | --- | --- | --- |
| 1 | [omnidev](https://github.com/himanshu748/omnidev) | Original | 2026-02-15 | Full-stack AI platform combining DevOps, scraping, vision, and storage workflows |
| 2 | [feb_challenge](https://github.com/himanshu748/feb_challenge) | Original | 2026-02-21 | End-to-end IPL analytics with large-scale dataset processing and interactive visualization |
| 3 | [eklavyasubmission](https://github.com/himanshu748/eklavyasubmission) | Original | 2026-01-18 | Education-focused AI explainer with structured exam-style output |
| 4 | [langchain-rag-tutorial-2026](https://github.com/himanshu748/langchain-rag-tutorial-2026) | Original | 2026-01-22 | Modern RAG patterns using agents, local model support, and streaming |
| 5 | [docs-agent](https://github.com/himanshu748/docs-agent) | OSS fork work | 2026-02-22 | Kubeflow documentation assistant architecture with RAG and K8s serving stack |

---

## Visual Project Gallery (Local Images)

All images below are stored in this repo under `assets/cards/` (no external image hosting).

<p align="center">
  <a href="https://github.com/himanshu748/omnidev"><img src="./assets/cards/omnidev.svg" alt="OmniDev project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/feb_challenge"><img src="./assets/cards/feb-challenge.svg" alt="IPL analysis project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/eklavyasubmission"><img src="./assets/cards/jee-neet-explainer.svg" alt="JEE NEET AI project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/langchain-rag-tutorial-2026"><img src="./assets/cards/langchain-rag.svg" alt="LangChain RAG project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/docs-agent"><img src="./assets/cards/docs-agent.svg" alt="Kubeflow docs agent project card" width="48%" /></a>
</p>

---

## Interactive Deep Dive

<details>
<summary><strong>OmniDev: platform architecture</strong></summary>

<br />

**Core modules**
- DevOps agent for AWS command execution
- Stealth scraping workflows via Playwright
- Vision/OCR assistant workflows
- S3-driven storage operations
- Location intelligence API endpoints

```mermaid
flowchart LR
  UI["Next.js Frontend"] --> API["FastAPI API Layer"]
  API --> AGENT["Agent Orchestrator"]
  AGENT --> LLM["OpenAI Models"]
  AGENT --> AWS["AWS APIs"]
  AGENT --> PW["Playwright Worker"]
  AWS --> S3["S3 Storage"]
```

</details>

<details>
<summary><strong>IPL evolution analysis: data pipeline</strong></summary>

<br />

**Dataset scale**
- 278,205 deliveries
- 1,169 matches
- 17 seasons (2008-2025)

**Output**
- 10 interactive Plotly visualizations
- Narrative findings around run-rate growth, bowling adaptation, and toss impact

```mermaid
flowchart LR
  RAW["Cricsheet Raw Files"] --> CLEAN["Python Data Processing"]
  CLEAN --> DATASETS["Structured CSV Datasets"]
  DATASETS --> NB["Analysis Notebook"]
  NB --> VIS["Interactive Plotly Visuals"]
  VIS --> STORY["Findings and Storytelling"]
```

</details>

<details>
<summary><strong>AI Concept Explainer: product loop</strong></summary>

<br />

**Product direction**
- Topic input for JEE/NEET syllabus areas
- Step-by-step explanations, worked examples, and MCQs
- Math rendering and exam-oriented learning flow

```mermaid
sequenceDiagram
  participant S as Student
  participant UI as React Frontend
  participant API as Edge Function
  participant M as AI Model
  S->>UI: Enter topic
  UI->>API: Request explanation
  API->>M: Prompt with exam constraints
  M->>API: Structured explanation output
  API->>UI: Steps + example + MCQ
  UI->>S: Render formatted learning module
```

</details>

---

## Open Source Fork Activity (Current)

| Repository | Updated | Focus |
| --- | --- | --- |
| [docs-agent](https://github.com/himanshu748/docs-agent) | 2026-02-22 | Kubeflow documentation RAG assistant |
| [sdk](https://github.com/himanshu748/sdk) | 2026-02-22 | Python SDK for AI workloads on Kubernetes |
| [trainer](https://github.com/himanshu748/trainer) | 2026-02-22 | Distributed training and LLM fine-tuning workflows |
| [pipelines](https://github.com/himanshu748/pipelines) | 2026-02-22 | Kubeflow pipelines ecosystem work |
| [gemini-cli](https://github.com/himanshu748/gemini-cli) | 2026-02-22 | Terminal-native AI agent tooling |
| [jenkins](https://github.com/himanshu748/jenkins) | 2026-02-22 | CI/CD platform fork maintenance |

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/LiveKit-FF5A5F?style=flat-square&logo=livekit&logoColor=white" alt="LiveKit" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=himanshu748&theme=tokyonight" alt="GitHub Stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=himanshu748&theme=tokyonight" alt="Top Languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=himanshu748&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## Contact

- Email: [jhahimanshu653@gmail.com](mailto:jhahimanshu653@gmail.com)
- LinkedIn: [linkedin.com/in/himanshu748](https://linkedin.com/in/himanshu748)
- GitHub: [github.com/himanshu748](https://github.com/himanshu748)
