# Ayush Jadaun

**Co-Founder & CTO @ [Dreamvator](https://dreamvator.com) · Building distributed systems, AI infrastructure, and developer tools**

[![Portfolio](https://img.shields.io/badge/Portfolio-ayushjadaun.vercel.app-0E75B6?style=flat-square&logo=vercel&logoColor=white)](https://ayushjadaun.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ayush--jadaun-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-jadaun-677199311/)
[![Email](https://img.shields.io/badge/Email-ayushjadaun6@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ayushjadaun6@gmail.com)
[![npm](https://img.shields.io/badge/npm-@psyqueue/core-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@psyqueue/core)

---

## About

I'm a 2nd-year ECE student at MNNIT Allahabad, currently building [Dreamvator](https://dreamvator.com) — aviation stealth startup. I architect and ship full production systems: from distributed job queues and multi-agent orchestration to mobile apps, payment infrastructure, and cloud deployments.

My work sits at the intersection of **distributed systems**, **AI/ML**, and **systems engineering**. I care about building things that are technically rigorous and solve real problems.

- Currently: CTO & Co-Founder at Dreamvator (React Native · Node.js · AWS ECS Fargate)
- Published: [`@psyqueue/core`](https://www.npmjs.com/package/@psyqueue/core) on npm, [`tbuddy`](https://pypi.org/project/tbuddy/) and [`marlos`](https://pypi.org/project/marlos/) on PyPI
- Executive at **Computer Coding Club, MNNIT Allahabad**
- Open to internship and collaboration opportunities in distributed systems, AI infrastructure, and full-stack engineering

---

## Projects

### [`PsyQueue`](https://github.com/ayush-jadaun/psyqueue) — Micro-Kernel Distributed Job Queue
[![npm version](https://img.shields.io/npm/v/@psyqueue/core.svg?style=flat-square)](https://www.npmjs.com/package/@psyqueue/core)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Plugin-architecture job queue in TypeScript. ~500-line kernel with 20+ plugins covering DAG workflows, Saga compensation, multi-tenancy, circuit breakers, and exactly-once delivery. Outperforms BullMQ via fused `ackAndFetch` (2 Redis round-trips vs 3), hybrid list + sorted-set dequeue, and hash field packing (13 vs 30 fields per HGETALL). Ships SQLite/Redis/Postgres backends — zero infra to start.

`TypeScript` `Redis` `PostgreSQL` `SQLite` `Node.js`

---

### [`DAIOS`](https://github.com/ayush-jadaun/daios) — Distributed Autonomous Intelligent Orchestration System
[![Demo](https://img.shields.io/badge/Demo-Google%20Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1H6Zmum1GoUS-jChWQhtYEZOrBOjBfJpU)

Multi-agent orchestration system where an Orchestra Agent decomposes tasks and assigns them to specialized Dev, Debug, and Ops agents via a Redis pub/sub message bus. Each agent runs a ReAct loop backed by Gemini 2.0 Flash with vector + session memory. Supports sequential and parallel execution with retry logic and fault-tolerant timeout budgets.

`Python` `Node.js` `Redis` `FastAPI` `Docker` `Gemini`

---

### [`MarlOS`](https://github.com/ayush-jadaun/MarlOS) — Multi-Agent Reinforcement Learning Operating System
[![PyPI](https://img.shields.io/pypi/v/marlos?style=flat-square)](https://pypi.org/project/marlos/)
[![Demo](https://img.shields.io/badge/Demo-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/EGv7Z3kXv30)

Fully decentralized P2P distributed OS — no central orchestrator. Nodes communicate via ZeroMQ gossip, authenticate with Ed25519 signatures, and self-heal by migrating jobs on failure. Each node runs a PPO agent (25-dim state vector) for cooperative bid/forward/defer decisions. Includes a fairness-aware economic layer (MarlCredits) with progressive taxation and starvation prevention. Built at Hack36 9.0.

`Python` `PyTorch` `Stable Baselines3` `ZeroMQ` `Docker`

---

### [`TBuddy`](https://github.com/ayush-jadaun/tbuddy) — Multi-Agent Travel Planning System
[![PyPI](https://img.shields.io/pypi/v/tbuddy?style=flat-square)](https://pypi.org/project/tbuddy/)

5 specialized agents (Weather, Events, Maps, Budget, Itinerary) orchestrated via Redis pub/sub with real-time SSE streaming. LangGraph-based stateful planning with MCP architecture. Each agent runs in an isolated Docker container with configurable replicas.

`Python` `FastAPI` `Redis` `LangGraph` `Docker` `Gemini`

---

### [`Dreamvator`](https://dreamvator.com) — Structured Pilot Training Platform
[![Website](https://img.shields.io/badge/Website-dreamvator.com-1A3C6E?style=flat-square&logo=globe&logoColor=white)](https://dreamvator.com)
STEALTH AVIATION STARTUP



---

### [`AllProfanity`](https://github.com/ayush-jadaun/allprofanity) — Multi-Language Profanity Filter
[![npm version](https://img.shields.io/npm/v/allprofanity.svg?style=flat-square)](https://www.npmjs.com/package/allprofanity)
[![npm downloads](https://img.shields.io/npm/dw/allprofanity?style=flat-square&color=CB3837)](https://www.npmjs.com/package/allprofanity)

Zero-dependency profanity filter supporting 9 languages (English, Hindi, Hinglish, Bengali, Tamil, Telugu, French, German, Spanish) including native scripts (Devanagari, Bengali, Tamil, Telugu). 160+ weekly downloads. Customizable word lists, character-level and word-level replacement, built entirely in TypeScript.

`TypeScript` `Node.js` `npm`

---

## Achievements

| | Competition | Year |
|---|---|---|
| 🥇 | Winner — Hactivate, Botrush 3.0 (Robotics Club, MNNIT) | 2025 |
| 🥇 | Winner — Galactic Heist, Botrush 3.0 (Astronomy Club, MNNIT) | 2025 |
| 🥇 | Winner — Robowars, Botrush 3.0 (Robotics Club, MNNIT) | 2025 |
| 🥇 | Triple Winner — CodeSangam 2025 (DroidRush, Logical Rhythm, ContriHub) | 2025 |
| 🥇 | Winner — AIML Hackathon, Culrav/Avishkar (MNNIT) | 2024 |
| 🥈 | Runner-up — Quinthalon Mock Interview, ES Society (MNNIT) | 2024 |
| 🏆 | 2nd Runner-up — DevJam, Weekend of Code (MNNIT) | 2025 |
| 🏆 | 10th Place — Hack36 9.0 | 2025 |

---

## Stack

```
Languages     C++  Python  TypeScript  JavaScript  Rust
Frontend      React  React Native  Next.js  Tailwind CSS
Backend       Node.js  Express  FastAPI  PostgreSQL  MongoDB  Redis  Supabase
AI / ML       PyTorch  TensorFlow  LangGraph  Stable Baselines3  Gemini
DevOps        AWS (ECS · RDS · CloudFront)  Terraform  Docker  Nginx
```

---

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ayush-jadaun&show_icons=true&theme=tokyonight&count_private=true&hide_rank=false" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ayush-jadaun&layout=compact&theme=tokyonight" height="150"/>
</div>

---

<sub>📫 ayushjadaun6@gmail.com · [linkedin.com/in/ayush-jadaun-677199311](https://www.linkedin.com/in/ayush-jadaun-677199311/) · [ayushjadaun.vercel.app](https://ayushjadaun.vercel.app)</sub>
