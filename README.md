<div align="center">

```
┌──────────────────────────────────────────────┐
│                                                │
│   GUBBA  YASODHAR                             │
│   Full-Stack Engineer                         │
│                                                │
└──────────────────────────────────────────────┘
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasodhar-gubba-18aa84209/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/YasodharGubba05)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yasodhargubba@gmail.com)

</div>

<br>

## `> whoami`

```yaml
name: Gubba Yasodhar
role: Aspiring Full-Stack Engineer (seeking internships)
university: SRM University AP  |  CSE '27
focus:
  - Real-time systems (WebSockets, Socket.io, WebRTC)
  - RAG pipelines & LLM integration
  - Scalable system design (RBAC, microservices)
currently_learning: [Docker, PostgreSQL advanced, Drizzle ORM, Postman]
open_to: Campus placements · Internships · Full-Stack / AI roles
```

<br>

## `> cat featured.md`

<table>
<tr>
<td>

### 🧠 Synapse — Live Meeting Intelligence Platform  `⭐ lead project`
> A meeting copilot, not a note-taker — real-time audio capture, transcription, and structured extraction, all live.

**Stack:** Python · FastAPI · React · Groq Whisper · Llama 3 · SQLAlchemy · SQLite · Web Audio API · SSE

- 🎙️ Real-time pipeline: live audio → **Groq Whisper** transcription → LLM extraction loop, streamed straight into a React workspace via **SSE**
- 🧩 Structured output enforced with **Pydantic** schema validation, persisted through a normalized **SQLAlchemy** layer — with an empty-schema fallback so a bad LLM response never crashes a live session
- 🔐 Zero server-side credential exposure: Groq API keys live only in browser `sessionStorage`, injected per-request via a custom header, never stored server-side

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/YasodharGubba05/Synapse)

</td>
</tr>
</table>

<br>

## `> ls projects/`

<table>
<tr>
<td width="50%" valign="top">

### 🗂️ ReportMaster AI
> Full-stack financial document intelligence platform

**Stack:** FastAPI · pgvector · Groq Llama 3.3-70B · PyMuPDF · all-MiniLM-L6-v2

- Token-aware chunking (500 tokens, 50-token overlap via tiktoken)
- Multi-tenant vector isolation with pgvector
- Grounding-enforced prompting + SSE streaming to React frontend
- Context-faithful generation — zero hallucination policy

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/YasodharGubba05/ReportMaster-AI)

</td>
<td width="50%" valign="top">

### ⚡ BondBox
> Full-stack real-time collaborative study platform

**Stack:** React · TypeScript · FastAPI · Supabase · WebRTC · Upstash Redis

- Peer-to-peer video/voice via WebRTC, WebSocket signaling for room management
- Supabase Postgres with Row Level Security enforced at the DB layer
- Upstash Redis for leaderboard caching, rate limiting, live presence

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/YasodharGubba05/Bond-Box)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AgileAI
> Full-stack sprint risk & burnout prediction platform

**Stack:** Python · XGBoost · FastAPI · Node.js · Socket.io · Docker

- 95.2% sprint risk prediction accuracy, 97.1% burnout detection accuracy
- ML-powered forecasting with XGBoost on team velocity signals
- Real-time Kanban via Socket.io, Dockerized microservices

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/YasodharGubba05/Agile-AI)

</td>
<td width="50%" valign="top">

### 🔗 TrimLink
> Full-stack URL shortener with user dashboard

**Stack:** Node.js · Express · Drizzle ORM · JWT · EJS

- Responsive frontend with link management dashboard
- Secure user-scoped link creation & analytics
- JWT authentication + full redirect pipeline
- Clean REST API with input validation

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/YasodharGubba05/TrimLink)

</td>
</tr>
</table>

<br>

## `> cat skills.json`

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-6BA63A?style=flat-square)

**Backend & Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)

**AI / ML**

![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Llama](https://img.shields.io/badge/Llama_3-0467DF?style=flat-square&logo=meta&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Databases & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

<br>

## `> experience --verbose`

```
┌─────────────────────────────────────────────────────────┐
│  💻  Full Stack Developer Intern · SRM University AP    │
│      June 2025 – August 2025                            │
│                                                           │
│  ▸ Built a fake-news detection platform: React frontend  │
│    + FastAPI backend + ML inference pipeline             │
│  ▸ Built APIs for NLP preprocessing & real-time          │
│    prediction with optimized response times               │
│  ▸ Evaluated models on accuracy vs. latency vs.           │
│    deployment feasibility for production use               │
└─────────────────────────────────────────────────────────┘
```

<br>

## `> stats --user YasodharGubba05`

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=YasodharGubba05&theme=tokyonight" />

<br><br>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=YasodharGubba05&theme=tokyonight" width="48%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=YasodharGubba05&theme=tokyonight" width="48%" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YasodharGubba05&theme=tokyo-night" />

</div>
