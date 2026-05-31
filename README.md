<p align="center">
  <img src="./assets/himanshu-ai-workbench.svg" alt="Himanshu AI Workbench" width="100%" />
</p>

<h1 align="center">Himanshu Kumar</h1>

<p align="center">
  <strong>Full Stack AI Developer</strong><br />
  AI Agents | Full Stack Systems | Data Products | Developer Tools
</p>

<p align="center">
  <a href="mailto:jhahimanshu653@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/himanshu748"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/himanshu748?tab=repositories"><img src="https://img.shields.io/badge/All%20Repos-181717?style=for-the-badge&logo=github&logoColor=white" alt="All Repositories" /></a>
</p>

<p align="center">
  Building practical AI products with reliable APIs, polished interfaces, and production-minded engineering.
</p>

---

## How I Build

| Area | Engineering focus |
| --- | --- |
| Agent systems | Tool calling, structured output, reliable degradation |
| Product delivery | FastAPI/Express backends with React/Next.js frontends |
| Data products | Multi-source analysis, dashboards, reproducible pipelines |
| Realtime UX | Streaming updates, Socket.IO/SSE flows, live status feedback |
| Open source | Fast iteration across forks, hackathons, and upstream ecosystems |

---

## Best Projects (Snapshot: 2026-05-31)

Selection logic: recency of updates, technical depth, and direct end-user usefulness.

| Rank | Project | Type | Updated | Why it stands out |
| --- | --- | --- | --- | --- |
| 1 | [reporank](https://github.com/himanshu748/reporank) | Original | 2026-05-29 | Open source impact and funding-readiness agent using Coral SQL, FastAPI, and Qwen |
| 2 | [vedaai-assessment-creator](https://github.com/himanshu748/vedaai-assessment-creator) | Original | 2026-05-24 | Full-stack teacher workflow for AI-generated question papers, PDFs, and live job tracking |
| 3 | [omnidev](https://github.com/himanshu748/omnidev) | Original | 2026-05-18 | AI developer platform combining DevOps, scraping, vision, storage, and location tools |
| 4 | [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent) | Original | 2026-04-13 | Crypto research agent on ElizaOS and Nosana with open market, DeFi, RSS, and Solana data |
| 5 | [prism-mistral-hackathon](https://github.com/himanshu748/prism-mistral-hackathon) | Original | 2026-02-28 | Multi-agent decision intelligence with Mistral tools, live debate, SSE streaming, and D3 graphs |
| 6 | [feb_challenge](https://github.com/himanshu748/feb_challenge) | Original | 2026-02-21 | IPL analytics across 278K+ deliveries, 1,169 matches, and 17 seasons |

---

## Visual Project Gallery (Local Images)

All images below are stored in this repo under `assets/cards/` (no external image hosting).

<p align="center">
  <a href="https://github.com/himanshu748/reporank"><img src="./assets/cards/reporank.svg" alt="RepoRank project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/vedaai-assessment-creator"><img src="./assets/cards/vedaai.svg" alt="VedaAI project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/omnidev"><img src="./assets/cards/omnidev.svg" alt="OmniDev project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/sentinel-nosana-agent"><img src="./assets/cards/sentinel.svg" alt="Sentinel project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/prism-mistral-hackathon"><img src="./assets/cards/prism.svg" alt="Prism project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/feb_challenge"><img src="./assets/cards/feb-challenge.svg" alt="IPL analysis project card" width="48%" /></a>
</p>

---

## Interactive Deep Dive

<details>
<summary><strong>RepoRank: impact analysis flow</strong></summary>

<br />

**Core modules**
- Cross-source Coral SQL joins over GitHub, PyPI/npm, HackerNews, and Open Collective
- FastAPI endpoint for repo analysis
- Qwen-powered narrative report generation
- Impact card with score, radar chart, pitch, and grant matches

```mermaid
flowchart LR
  UI["Dashboard"] --> API["FastAPI /analyze"]
  API --> ORC["RepoRank Agent"]
  ORC --> CORAL["Coral SQL"]
  CORAL --> GH["GitHub"]
  CORAL --> PKG["PyPI/npm"]
  CORAL --> HN["HackerNews"]
  CORAL --> OC["Open Collective"]
  ORC --> LLM["Qwen Report"]
  LLM --> CARD["Impact Card"]
```

</details>

<details>
<summary><strong>VedaAI: assessment generation pipeline</strong></summary>

<br />

**Core modules**
- Teacher assignment wizard with PDF/TXT uploads
- Express backend with MongoDB, Redis, BullMQ, and Socket.IO
- Background worker for LLM generation and PDF compilation
- Offline fallback generation for sandbox resilience

```mermaid
sequenceDiagram
  participant T as Teacher
  participant UI as Next.js UI
  participant API as Express API
  participant Q as BullMQ
  participant W as Worker
  participant PDF as PDFKit
  T->>UI: Create assessment
  UI->>API: Upload details and files
  API->>Q: Queue generation job
  Q->>W: Process job
  W->>PDF: Compile question paper
  W->>UI: Stream status with Socket.IO
```

</details>

<details>
<summary><strong>Sentinel: crypto research agent</strong></summary>

<br />

**Core modules**
- ElizaOS agent runtime
- Market, token, news, research, and Nosana ecosystem actions
- CoinGecko, DeFiLlama, RSS, and Solana public RPC providers
- Nosana-hosted model inference with cached responses

```mermaid
flowchart LR
  USER["Research Query"] --> AGENT["ElizaOS Agent"]
  AGENT --> ACTIONS["Research Actions"]
  ACTIONS --> CG["CoinGecko"]
  ACTIONS --> DL["DeFiLlama"]
  ACTIONS --> RSS["RSS Feeds"]
  ACTIONS --> SOL["Solana RPC"]
  AGENT --> NOS["Nosana GPU Inference"]
  NOS --> REPORT["Data-backed Briefing"]
```

</details>

---

## Current Repository Map

| Track | Repositories |
| --- | --- |
| Agent products | [reporank](https://github.com/himanshu748/reporank), [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent), [prism-mistral-hackathon](https://github.com/himanshu748/prism-mistral-hackathon), [agent](https://github.com/himanshu748/agent) |
| Full-stack apps | [vedaai-assessment-creator](https://github.com/himanshu748/vedaai-assessment-creator), [omnidev](https://github.com/himanshu748/omnidev), [pr-review-agent](https://github.com/himanshu748/pr-review-agent), [Whack-a-bug](https://github.com/himanshu748/Whack-a-bug) |
| Data and notebooks | [feb_challenge](https://github.com/himanshu748/feb_challenge), [langchain-rag-tutorial-2026](https://github.com/himanshu748/langchain-rag-tutorial-2026), [deeplearning](https://github.com/himanshu748/deeplearning) |
| Open-source forks | [coral](https://github.com/himanshu748/coral), [OpenMetadata](https://github.com/himanshu748/OpenMetadata), [zed](https://github.com/himanshu748/zed), [gemini-cli](https://github.com/himanshu748/gemini-cli) |

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
