<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                          HEADER  ·  HERO BANNER                          -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="./assets/himanshu-ai-workbench.svg" alt="Himanshu AI Workbench" width="100%" />
</p>

<h1 align="center">Himanshu Kumar</h1>

<!-- ── Typing subtitle ─────────────────────────────────────────────────── -->
<p align="center">
  <a href="https://github.com/himanshu748">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=70A5FD&center=true&vCenter=true&width=760&lines=Full-Stack+AI+Developer;AI+Agents+%C2%B7+Full-Stack+Systems+%C2%B7+Data+Products;Reliable+APIs+%C2%B7+Polished+interfaces+%C2%B7+Production-minded;Idea+%E2%86%92+MVP+%E2%86%92+Ship.+Fast." alt="Typing SVG" />
  </a>
</p>

<!-- ── Social / contact badges ─────────────────────────────────────────── -->
<p align="center">
  <a href="mailto:jhahimanshu653@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/himanshu748"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://huggingface.co/HIMANSHUKUMARJHA"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-FFD21E?style=for-the-badge&logoColor=black" alt="HuggingFace" /></a>
  <a href="https://github.com/himanshu748?tab=repositories"><img src="https://img.shields.io/badge/All%20Repos-181717?style=for-the-badge&logo=github&logoColor=white" alt="All Repositories" /></a>
</p>

<!-- ── Live counters ───────────────────────────────────────────────────── -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=himanshu748&label=Profile%20views&color=70A5FD&style=flat-square" alt="views" />
  <img src="https://img.shields.io/github/followers/himanshu748?label=Followers&style=flat-square&color=BB9AF7" alt="followers" />
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

## Best Projects (Snapshot: 2026-06-16)

Selection logic: technical depth, product completeness, current traffic, verification quality, and portfolio breadth.

| Rank | Project | Type | Updated | Why it stands out |
| --- | --- | --- | --- | --- |
| 1 | [reporank](https://github.com/himanshu748/reporank) | Original | 2026-06-09 | Open-source impact and funding-readiness agent that joins GitHub, PyPI/npm, Hacker News, and Open Collective signals through Coral SQL, then generates a grant-ready report with Qwen |
| 2 | [exam-panic-rescue](https://github.com/himanshu748/exam-panic-rescue) | Original | 2026-06-12 | Privacy-minded Gradio study assistant with strong clone traffic, multimodal small-model paths, real-user validation, and a complete student rescue workflow |
| 3 | [pixel-digit-recognizer](https://github.com/himanshu748/pixel-digit-recognizer) | Original | 2026-06-13 | Browser-only MNIST recognizer with the strongest recent profile traffic, four stars, Pyodide-powered NumPy inference, and no backend dependency |
| 4 | [FormOS](https://github.com/himanshu748/FormOS) | Original | 2026-06-13 | Full-stack retro OS form builder with Next.js, tRPC, Drizzle, PostgreSQL, public forms, QR sharing, analytics, and generated Scalar API docs |
| 5 | [omnidev](https://github.com/himanshu748/omnidev) | Original | 2026-06-04 | Local-first AI developer platform with configurable APIs, Gemini code generation, browser-tested frontend, and FastAPI services |
| 6 | [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent) | Original | 2026-06-04 | Crypto research agent on ElizaOS and Nosana with market, DeFi, RSS, Solana, provider validation, and 70-test coverage |

---

## Visual Project Gallery (Local Images)

All images below are stored in this repo under `assets/cards/` (no external image hosting).

<p align="center">
  <a href="https://github.com/himanshu748/reporank"><img src="./assets/cards/reporank.svg" alt="RepoRank project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/jee-neet-ai-concept-explainer"><img src="./assets/cards/jee-neet-explainer.svg" alt="JEE NEET AI concept explainer project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/python-automation-training-toolkit"><img src="./assets/cards/python-automation-toolkit.svg" alt="Python Automation Toolkit project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/documate-ai"><img src="./assets/cards/docs-agent.svg" alt="DocuMate AI project card" width="48%" /></a>
</p>

<p align="center">
  <a href="https://github.com/himanshu748/omnidev"><img src="./assets/cards/omnidev.svg" alt="OmniDev project card" width="48%" /></a>
  <a href="https://github.com/himanshu748/sentinel-nosana-agent"><img src="./assets/cards/sentinel.svg" alt="Sentinel project card" width="48%" /></a>
</p>

---

## Interactive Deep Dive

<details>
<summary><strong>RepoRank: funding-readiness agent</strong></summary>

<br />

**Core modules**
- FastAPI analysis endpoint with a Coral SQL orchestration layer
- Cross-source signals from GitHub, PyPI/npm, Hacker News, and Open Collective
- Hugging Face Qwen narrative generation for impact scoring and grant matching
- Shareable dashboard output with score, pitch, radar chart, and matching programs

```mermaid
flowchart LR
  USER["Repository URL"] --> API["FastAPI Analyze API"]
  API --> CORAL["Coral SQL Query"]
  CORAL --> SOURCES["GitHub + Packages + HN + Funding"]
  SOURCES --> MODEL["Qwen Report Generator"]
  MODEL --> CARD["Impact Card + Grant Matches"]
```

</details>

<details>
<summary><strong>Exam Panic Rescue: study triage workflow</strong></summary>

<br />

**Core modules**
- Gradio product flow for one stressed student, one exam, and one time box
- Small-model routes with MiniCPM, Nemotron, and local llama.cpp support
- Vision-capable syllabus/photo handling plus text-only fallback paths
- Privacy-minded traces with anonymized real-user validation

```mermaid
flowchart LR
  STUDENT["Panic Dump + Topics"] --> TRIAGE["Topic Triage"]
  TRIAGE --> PLAN["Rescue Plan"]
  PLAN --> DRILLS["Drill Deck"]
  DRILLS --> PROOF["Proof Target"]
  PROOF --> SHEET["Final Sheet + Receipt"]
```

</details>

<details>
<summary><strong>FormOS: full-stack form platform</strong></summary>

<br />

**Core modules**
- Turborepo workspace with Next.js, tRPC, Drizzle, and PostgreSQL
- Form editor, public form runner, QR sharing, and anonymous submissions
- Analytics dashboard with response table and per-field breakdowns
- Scalar docs generated from the live tRPC router

```mermaid
flowchart LR
  BUILDER["Form Builder"] --> TRPC["tRPC Procedures"]
  PUBLIC["Public Form"] --> TRPC
  TRPC --> DB["Drizzle + PostgreSQL"]
  DB --> ANALYTICS["Analytics Dashboard"]
  TRPC --> DOCS["Generated Scalar Docs"]
```

</details>

---

## Current Repository Map

| Track | Repositories |
| --- | --- |
| Best portfolio projects | [reporank](https://github.com/himanshu748/reporank), [exam-panic-rescue](https://github.com/himanshu748/exam-panic-rescue), [pixel-digit-recognizer](https://github.com/himanshu748/pixel-digit-recognizer), [FormOS](https://github.com/himanshu748/FormOS), [omnidev](https://github.com/himanshu748/omnidev), [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent) |
| Agent products | [omnidev](https://github.com/himanshu748/omnidev), [sentinel-nosana-agent](https://github.com/himanshu748/sentinel-nosana-agent), [prism-mistral-hackathon](https://github.com/himanshu748/prism-mistral-hackathon), [prreviewiq-code-review-agent](https://github.com/himanshu748/prreviewiq-code-review-agent), [jee-neet-ai-concept-explainer](https://github.com/himanshu748/jee-neet-ai-concept-explainer) |
| Developer and automation tools | [python-automation-training-toolkit](https://github.com/himanshu748/python-automation-training-toolkit), [apivault-api-docs-generator](https://github.com/himanshu748/apivault-api-docs-generator), [pr-review-agent](https://github.com/himanshu748/pr-review-agent), [langchain-rag-tutorial-2026](https://github.com/himanshu748/langchain-rag-tutorial-2026), [webmcptutorial](https://github.com/himanshu748/webmcptutorial) |
| Full-stack products | [FormOS](https://github.com/himanshu748/FormOS), [launchproof-ai](https://github.com/himanshu748/launchproof-ai), [opportunity-scout](https://github.com/himanshu748/opportunity-scout), [hireiq-recruiting-assistant](https://github.com/himanshu748/hireiq-recruiting-assistant), [documate-ai](https://github.com/himanshu748/documate-ai) |
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

## GitHub Analytics

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=himanshu748&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&title_color=70A5FD&icon_color=BB9AF7" alt="GitHub Stats" />
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=himanshu748&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&title_color=70A5FD" alt="Top Languages" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=himanshu748&theme=tokyonight&hide_border=true&ring=70A5FD&fire=BB9AF7&currStreakLabel=70A5FD" alt="GitHub Streak" />

</div>

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=himanshu748&bg_color=1a1b27&color=70A5FD&line=BB9AF7&point=ffffff&area=true&hide_border=true" alt="Activity Graph" />

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=himanshu748&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="Trophies" />

</div>

---

## Contribution Graph

<div align="center">
  <img src="https://raw.githubusercontent.com/himanshu748/himanshu748/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />
</div>

<sub>The snake auto-regenerates daily via <code>.github/workflows/snake.yml</code>. Run it once from the <strong>Actions</strong> tab to seed the first frame.</sub>

---

## 💖 Sponsor My Work

<div align="center">

**I build open AI products and developer tools — in the open, for free.**

If something I've shipped saved you time, sparked an idea, or you just want to back the next build,
sponsorship keeps the work shipping and the tools free for everyone.

<br />

<a href="https://github.com/sponsors/himanshu748">
  <img src="https://img.shields.io/badge/Sponsor%20on%20GitHub-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Sponsor" />
</a>

</div>

### What your sponsorship fuels

| Tier | Amount | You get |
| :---: | :---: | :--- |
| ☕ **Espresso** | `$5 / mo` | My genuine thanks + your name in the supporters list below |
| ⚡ **Builder** | `$15 / mo` | Above + early access to new tools and priority issue responses |
| 🚀 **Backer** | `$50 / mo` | Above + a monthly 30-min call — AI/agents, architecture, or your project |
| 🏆 **Patron** | `$100+ / mo` | Above + your logo/link featured here and across my project READMEs |

<div align="center">

*Prefer a one-off? GitHub Sponsors supports one-time gifts too — every bit is appreciated.*

<br />

**🌟 Current Sponsors**

<a href="https://github.com/sponsors/himanshu748"><img src="https://img.shields.io/badge/Be%20the%20first%20sponsor-%E2%9D%A4-EA4AAA?style=flat-square" alt="be first" /></a>

</div>

---

## Contact

- Email: [jhahimanshu653@gmail.com](mailto:jhahimanshu653@gmail.com)
- LinkedIn: [linkedin.com/in/himanshu748](https://linkedin.com/in/himanshu748)
- GitHub: [github.com/himanshu748](https://github.com/himanshu748)
