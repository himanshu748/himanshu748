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

## Best Projects (Snapshot: 2026-06-04)

Selection logic: recency of updates, technical depth, and direct end-user usefulness.

| Rank | Project | Type | Updated | Why it stands out |
| --- | --- | --- | --- | --- |
| 1 | [omnidev](https://github.com/himanshu748/omnidev) | Original | 2026-05-18 | Local-first AI developer platform with configurable APIs, Gemini code generation, browser-tested frontend, and FastAPI services |
| 2 | [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent) | Original | 2026-04-13 | Crypto research agent on ElizaOS and Nosana with market, DeFi, RSS, Solana, and 60-test coverage |
| 3 | [python-automation-training-toolkit](https://github.com/himanshu748/python-automation-training-toolkit) | Original | 2026-06-02 | Browser workspace and CLI for safe automation training across Hugging Face, AWS, S3, location, email, and gestures |
| 4 | [prism-mistral-hackathon](https://github.com/himanshu748/prism-mistral-hackathon) | Original | 2026-02-28 | Multi-agent decision intelligence with Mistral tools, live debate, SSE streaming, and D3 graphs |
| 5 | [ipl-evolution-data-analysis](https://github.com/himanshu748/ipl-evolution-data-analysis) | Original | 2026-02-21 | IPL analytics across 278K+ deliveries, 1,169 matches, and 17 seasons |
| 6 | [langchain-rag-tutorial-2026](https://github.com/himanshu748/langchain-rag-tutorial-2026) | Original | 2026-01-22 | Practical RAG tutorial repo for modern LangChain-style retrieval workflows |

---

## Visual Project Gallery (Local Images)

All images below are stored in this repo under `assets/cards/` (no external image hosting).

<p align="center">
  <a href="https://github.com/himanshu748/reporank"><img src="./assets/cards/reporank.svg" alt="RepoRank project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/python-automation-training-toolkit"><img src="./assets/cards/python-automation-toolkit.svg" alt="Python Automation Toolkit project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/omnidev"><img src="./assets/cards/omnidev.svg" alt="OmniDev project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/sentinel-nosana-agent"><img src="./assets/cards/sentinel.svg" alt="Sentinel project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/prism-mistral-hackathon"><img src="./assets/cards/prism.svg" alt="Prism project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/ipl-evolution-data-analysis"><img src="./assets/cards/feb-challenge.svg" alt="IPL analysis project card" width="48%" /></a>
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
<summary><strong>Python Automation Toolkit: training workflow</strong></summary>

<br />

**Core modules**
- Browser workspace split across overview, model, cloud, utility, and gesture pages
- CLI commands for readiness checks, safe config display, model summaries, S3, EC2, location, and email
- Feature-specific configuration gates so readiness works without secrets
- Local HTTP server with bounded JSON bodies, static path checks, and image validation

```mermaid
flowchart LR
  CLI["CLI + Browser UI"] --> CFG["Safe Readiness"]
  CFG --> HF["Hugging Face Workflows"]
  CFG --> AWS["EC2 + S3 Actions"]
  CFG --> UTIL["Location + Email Utilities"]
  CFG --> GEST["Browser Gesture Page"]
  HF --> OUT["Training Output"]
  AWS --> OUT
  UTIL --> OUT
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
| Agent products | [omnidev](https://github.com/himanshu748/omnidev), [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent), [prism-mistral-hackathon](https://github.com/himanshu748/prism-mistral-hackathon), [prreviewiq-code-review-agent](https://github.com/himanshu748/prreviewiq-code-review-agent) |
| Developer and automation tools | [python-automation-training-toolkit](https://github.com/himanshu748/python-automation-training-toolkit), [apivault-api-docs-generator](https://github.com/himanshu748/apivault-api-docs-generator), [pr-review-agent](https://github.com/himanshu748/pr-review-agent), [langchain-rag-tutorial-2026](https://github.com/himanshu748/langchain-rag-tutorial-2026) |
| Data and notebooks | [ipl-evolution-data-analysis](https://github.com/himanshu748/ipl-evolution-data-analysis), [deeplearning](https://github.com/himanshu748/deeplearning), [financeiq-notion-finance-tracker](https://github.com/himanshu748/financeiq-notion-finance-tracker), [autopm-notion-product-manager](https://github.com/himanshu748/autopm-notion-product-manager) |
| Open-source contributions and forks | [OpenMetadata](https://github.com/himanshu748/OpenMetadata), [hive](https://github.com/himanshu748/hive), [coral](https://github.com/himanshu748/coral), [the-gauntlet-voice-agent](https://github.com/himanshu748/the-gauntlet-voice-agent) |

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
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
