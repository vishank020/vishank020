<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:1e1e2e,50:313244,100:cba6f7&text=Vishank%20Singh&fontColor=cdd6f4&fontSize=60&fontAlignY=38&animation=fadeIn&desc=AI%20Engineer%20%C2%B7%20Agentic%20Systems%20%C2%B7%20Full-Stack&descAlignY=58&descSize=18&descColor=f5c2e7" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=2800&pause=900&color=CBA6F7&center=true&vCenter=true&width=640&height=40&lines=Building+agentic+AI+systems+that+actually+ship;LangGraph+%C2%B7+RAG+%C2%B7+Document+AI+%C2%B7+Tool-calling+agents;FastAPI+%C2%B7+Spring+Boot+%C2%B7+Next.js+%C2%B7+Angular;B.Tech+AI+%26+ML+%40+TCET+%C2%B7+Class+of+2027;Open+to+AI+%2F+ML+Engineering+internships" alt="Typing SVG" />

<br/>

[![Email](https://img.shields.io/badge/Email-cba6f7?style=for-the-badge&logo=gmail&logoColor=1e1e2e)](mailto:singhvishank20@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-89b4fa?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iIzFFMUUyRSI+PHBhdGggZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+)](https://www.linkedin.com/in/vishank-singh-762b7922b/)
[![Portfolio](https://img.shields.io/badge/Portfolio-a6e3a1?style=for-the-badge&logo=githubpages&logoColor=1e1e2e)](https://vishank020.github.io/portfolio-website/)
[![Resume](https://img.shields.io/badge/Resume-fab387?style=for-the-badge&logo=googledrive&logoColor=1e1e2e)](https://drive.google.com/file/d/18tWsamDXhjJoB8QdG8ILtja_lghP4nvd/view?usp=drive_link)

</div>

<br/>

## `~/about`

I build AI systems that are **predictable enough to trust in production**: agent graphs with clear routing, RAG with measured retrieval quality, and confirmation gates before an LLM touches real data. I also build the full-stack product around the model (auth, real-time, payments, deployment), because that's what turns a demo into something people can use.

```diff
+ Now      → multi-agent orchestration, document AI, evaluation-driven RAG
+ Learning → the deploy layer: Docker, Kubernetes, GitHub Actions, MLflow
+ Role     → Web Developer @ TCET ACM SIGAI
! Seeking  → AI / ML / Applied-LLM engineering internships
```

<br/>

## `~/featured`

<table>
<tr>
<td colspan="2">

### 🎓 Saarthi: AI admission & onboarding platform

An AI-assisted admission system for colleges. An **8-node LangGraph** agent graph routes each student query to the right agent: the admission copilot, document verification, RAG FAQ, or human escalation. A **two-tier OCR pipeline** (GLM-OCR + Qwen 2.5, with PaddleOCR as fallback) reads 35+ Indian identity and academic document types. Faculty mentors and admins review each application through a two-step verification flow with real-time chat.

| RAG Recall@3 | MRR | Retrieval p50 | RBAC leakage | Throughput |
|:---:|:---:|:---:|:---:|:---:|
| **90.0%** | **0.833** | **54 ms** | **0%** · 45 routes × 5 roles | **223 req/s** · 0% errors |

`LangGraph` `FastAPI` `Next.js 16` `ChromaDB` `Ollama` `PaddleOCR` `OpenCV` `PostgreSQL` `Redis` `Socket.IO` `Docker`

🔒 *Private repo · walkthrough on request*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💸 FinCoach AI

A **chat-first personal finance coach** for India. A **7-tool LLM agent** reads your real transactions, analyzes spending, and creates goals. Every write action asks for your confirmation first, and the agent has no delete tool at all.

- Groq Llama 3.3 70B, with NVIDIA NIM as fallback
- Token-by-token **SSE streaming** with tool-call cards
- **10 Indian languages** · INR-native advice (SIP, PPF, ELSS, 80C)
- 28 REST endpoints · Supabase Postgres with **row-level security**

`FastAPI` `Next.js 14` `Supabase` `Zustand` `Docker`

[**▶ Live demo**](https://fincoachai.vercel.app)

</td>
<td width="50%" valign="top">

### 📚 LearnSphere AI

A **college-first MOOC & LMS** that combines Udemy-style course sales, SWAYAM-style academic credentials, and AI tutoring.

- **Llama 3.1 70B (NVIDIA NIM)** writes quizzes from lecture transcripts
- *Spherie*, an in-player AI tutor that knows the current video timestamp
- Separate **payments microservice**: Razorpay, HMAC-verified webhooks, 80/20 royalty ledger
- Live classrooms over **STOMP WebSockets** · 37 views across 3 roles

`Spring Boot 3` `Angular 21` `PostgreSQL` `JWT` `WebSockets`

[**⌥ Source**](https://github.com/TCET-MOOC/LearnSphere-AI-Learning-platform)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🫂 Vayam

A **community platform for students & developers**: communities, posts, Q&A, anonymous discussions, and real-time DMs, with full moderation.

- **145 REST endpoints** · 32 tables · 51 Flyway migrations
- JWT in HttpOnly cookies + **TOTP 2FA** + email verification
- Postgres **full-text search** (tsvector + GIN indexes)
- Anonymous posts use an identity map that public feed queries never join
- DM inbox reduced from **81 → 4 queries**

`Spring Boot 3` `Angular 18` `PostgreSQL 16` `MinIO` `Nginx`

🔒 *Private repo · walkthrough on request*

</td>
<td width="50%" valign="top">

### 🌙 CozyPixels Web

A **zero-backend wallpaper gallery** for 939 wallpapers across Catppuccin, Nord & One Dark.

- Build-time pipeline: GitHub Trees API → **260 KB manifest** → static pages
- No database, no runtime API, **$0 hosting**
- Instant search, 24 categories, keyboard lightbox
- 3-theme design system with no hydration flash
- CI/CD to GitHub Pages · images served via jsDelivr CDN

`Next.js 16` `React 19` `TypeScript` `Tailwind v4` `GSAP`

[**▶ Live**](https://vishank020.github.io/CozyPixel.web/) · [**⌥ Source**](https://github.com/vishank020/CozyPixel.web)

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Links |
|---|---|---|
| **Portfolio Website** | React 19 portfolio with a 3-palette theme engine, an interactive terminal (`help`, `projects`, `resume`…) and a filterable project grid | [Live](https://vishank020.github.io/portfolio-website/) · [Source](https://github.com/vishank020/portfolio-website) |
| **TCET ACM SIGAI Website** | Frontend for TCET's ACM student chapter for AI & ML | [Source](https://github.com/vishank020/TCET-ACM-SIG-Website) |
| **Crop Disease Detection** | CNN that classifies 15 PlantVillage leaf-disease classes, with separate training and evaluation notebooks | [Source](https://github.com/vishank020/Crop-Disease-Detection-CNN) |

</details>

<br/>

## `~/stack`

<div align="center">

**AI / ML**<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn&theme=dark" />
<img src="https://img.shields.io/badge/LangGraph-1e1e2e?style=for-the-badge&logoColor=cba6f7&color=313244" height="48"/>
<img src="https://img.shields.io/badge/ChromaDB-1e1e2e?style=for-the-badge&color=313244" height="48"/>
<img src="https://img.shields.io/badge/Ollama-1e1e2e?style=for-the-badge&logo=ollama&logoColor=cdd6f4&color=313244" height="48"/>

**Backend**<br/>
<img src="https://skillicons.dev/icons?i=fastapi,java,spring,postgres,redis,mongodb&theme=dark" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=ts,react,nextjs,angular,tailwind&theme=dark" />

**Infra & Tools**<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,githubactions,vercel,linux,git&theme=dark" />

</div>

<br/>

## `~/stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=vishank020&show_icons=true&theme=catppuccin_mocha&hide_border=true&border_radius=12&include_all_commits=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishank020&layout=compact&theme=catppuccin_mocha&hide_border=true&border_radius=12&langs_count=6" height="165"/>

<img src="https://streak-stats.demolab.com?user=vishank020&theme=catppuccin-mocha&hide_border=true&border_radius=12" width="60%"/>

<br/><br/>

<img src="https://raw.githubusercontent.com/vishank020/vishank020/output/github-contribution-grid-snake-dark.svg" width="95%"/>

</div>

<br/>

<div align="center">

<sub>Building something with agents, RAG, or messy real-world documents? <a href="mailto:singhvishank20@gmail.com">Let's talk.</a></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:cba6f7,50:313244,100:1e1e2e&section=footer" width="100%"/>

</div>
