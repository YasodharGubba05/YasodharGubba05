<div align="center">

# Hi, I'm Yasodhar 👋

### Full-Stack Engineer building systems that turn static, after-the-fact experiences into live, real-time ones.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/YasodharGubba05)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasodhar-gubba-18aa84209/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yasodhargubba@gmail.com)

</div>

---

### About Me

I'm a final-year CS student at SRM University AP (2023–2027, CGPA 8.82), and I build full-stack products where the hard part isn't the CRUD — it's the real-time layer: WebSockets that hold up under concurrency, credential models that stay secure without a server-side vault, ML pipelines that have to be *right*, not just *shipped*. I'd rather go deep on one hard engineering problem than stack up features.

Currently sharpening: **Docker**, **PostgreSQL internals**, **Drizzle ORM**, **Postman**. Open to full-stack / AI-systems internships and new-grad roles.

---

## 🚀 Featured Work

### 🧠 [Synapse — Live Meeting Intelligence Platform](https://github.com/YasodharGubba05/Synapse)
*Replaces passive note-taking with a real-time meeting copilot.*

Captures live audio, transcribes it via **Groq Whisper**, and runs it through an LLM extraction loop that turns raw conversation into structured, persisted intelligence — as the meeting happens, not after.

- ⚡ **Real-time NLP loop:** streams trimmed transcript windows to a FastAPI backend, enforces structured output with **Pydantic schema validation**, and persists sentiment, prioritized action items, and decisions via a normalized **SQLAlchemy ORM** — with an empty-schema fallback so a bad LLM response never crashes a live session.
- 🔐 **Zero server-side credential exposure:** Groq API keys live only in browser `sessionStorage`, injected per-request via a custom header and consumed transiently by the backend — enabling a safe public deployment with no key storage on the server at all.
- 🎙️ Built on the **Web Audio API** for capture, **SSE** for live updates, and a **React** workspace on top.

`Python` `FastAPI` `React` `Groq` `Whisper` `Llama 3` `SQLite` `SQLAlchemy` `Web Audio API` `SSE`

---

### ⚡ [BondBox — Real-Time Collaborative Study Platform](https://github.com/YasodharGubba05/Bond-Box)
*Video, voice, and presence for concurrent users — built on WebRTC, not a video SDK.*

- 📡 **Peer-to-peer video/voice via WebRTC**, with a **WebSocket**-based signaling layer handling room management and live presence tracking across concurrent users.
- 🧩 **Modular FastAPI backend** (separate routers for rooms, users, and WebSocket management) backed by **Supabase PostgreSQL**, with **Row Level Security** enforcing per-user data access at the database layer — not just in application code.
- 🚦 **Upstash Redis** for leaderboard caching, API rate limiting, and real-time presence — cutting database load and keeping state consistent across distributed connections.

`React` `TypeScript` `FastAPI` `Supabase` `WebRTC` `WebSockets` `Upstash Redis` `Zustand` `Tailwind CSS`

---

### 🤖 [AgileAI — Intelligent Project Management Platform](https://github.com/YasodharGubba05/Agile-AI)
*A Kanban tool that predicts sprint risk and burnout before they happen.*

- 🎯 **95.2% accuracy** on sprint risk prediction and **97.1% accuracy** on burnout detection, using **XGBoost** models trained on team velocity signals.
- 🏗️ Built the backend end-to-end: **FastAPI microservices** for prediction, task estimation, and burnout detection, with normalized **PostgreSQL** schemas and optimized queries.
- 🔄 **Real-time Kanban collaboration** via **Socket.io** for concurrent multi-user task updates, all **Dockerized** for consistent, scalable multi-service deployment.

`Python` `FastAPI` `Node.js` `Express.js` `React` `MongoDB` `Socket.io` `Docker` `JWT` `XGBoost`

---

## 🛠️ Tech Stack

<div align="center">

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data & AI/ML**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![RAG/LLM](https://img.shields.io/badge/RAG_%2F_LLM-412991?style=flat-square&logo=openai&logoColor=white)

**DevOps & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

<div align="center">

## 📊 GitHub Stats

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=YasodharGubba05&theme=tokyonight" />

<br>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=YasodharGubba05&theme=tokyonight" width="48%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=YasodharGubba05&theme=tokyonight" width="48%" />

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YasodharGubba05&theme=tokyo-night" />

<br><br>

📫 **Let's talk:** [yasodhargubba@gmail.com](mailto:yasodhargubba@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yasodhar-gubba-18aa84209/)

</div>
