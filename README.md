# Dmitry Starodubtsev

Backend & AI engineer. Building production RAG pipelines, tool-call ing agents with memory, and multi-tenant back ends. Michigan State CS '26.

---

## Product ion Work

Production work is under NDA. OpsCore below is a demo built to show the kind of systems I work on day to day.

---

## Other Projects
 
**[OpsCore](https://github.com/stdmitry-aps/opscore)**
Small demo of an HR and operations  platform I'm building at work (production wo rk under NDA). Multi-tenant RBAC where permis sions are validated at import time so a misco nfigured perm breaks the server on startup, n ot at 2am when someone triggers the wrong end point. AI assistant that runs as a Celery tas k (not a streaming response) so it finishes e ven if the client disconnects. Two-stage RAG:  Qdrant for candidate retrieval, cross-encode r for reranking. Short-term agent memory in R edis, long-term in Postgres.
`Django REST` `N ext.js 14` `PostgreSQL` `Redis` `Celery` `Qdr ant` `Claude API`

**[Scheduler](https://github.com/stdmitry04/scheduler)**
World-agnostic  stride scheduler for real-time agent simulat ions. Any world plugs in via a single DoActio n interface. 4-tier priority system (CRITICAL /GAMEPLAY/ECONOMY/COSMETIC) with frame budget s and an async EventQueue for deferred action s. Scales to 50,000+ concurrent agents, compi led to WebAssembly via Emscripten.
`C++23` `W ebAssembly` `Emscripten`

**[QuiKard](https://github.com/stdmitry04/quikard)**
Digital bus iness card -- create in under a minute, expor t to Apple Wallet, share via NFC tap.
`Next.j s 15` `FastAPI` `PostgreSQL` `Apple Wallet AP I`

**[Volunteer Matchmaker](https://github.com/stdmitry04/Volunteer_Matchmaker)**
Composi te-scoring volunteer match system (proximity,  skills, urgency, reliability) with Ethereum  smart contracts for on-chain donation trackin g. SpartaHack XI Blockchain Track 3rd Place.
 `Next.js 15` `Django REST` `Solidity` `Gemini  AI`

**[CourseChecker](https://github.com/neontap/spartahack)**
Course review aggregator  -- only verified university students (school  email) can submit. Tracks 5 rating dimensions  per professor and semester.
`Next.js 14` `Su pabase` `GPT-4` `TypeScript`

---

## Stack

 **AI/ML:** RAG Systems - Vector Search (Qdran t) - LLM Tool Calling - Cross-encoder Reranki ng - Per-user Memory - Eval Design

**Backend :** Python - Django REST - FastAPI - Celery -  Node.js - RBAC - Stripe

**Frontend:** TypeS cript - React - Next.js - Tailwind CSS

**Inf ra:** AWS (ECS, RDS, S3) - Terraform - Docker  - CI/CD - PostgreSQL - Redis

---

## Educat ion

Michigan State University -- B.S. Comput er Science, Business Minor - GPA 3.75 - May 2026

---

[Portfolio](https://dmitrystarodubt sev.com) - [LinkedIn](https://linkedin.com/in /stdmitry04) - starodu5@gmail.com 
