# Dmitry Starodubtsev

Backend & AI engineer. Building production RAG pipelines, tool-calling agents with memory, and multi-tenant backends. Michigan State CS '26.

---

## Production Work

Most production work is under NDA. OpsCore below is a demo built to show the kind of systems I work on day to day.

**Safety Straw**
Full-stack build for a seed-stage startup making straws that glow when a drink is spiked. Stripe-integrated B2C and B2B checkout, async notification system, and an AI support agent that resolved 80%+ of customer inquiries autonomously.
`Node.js` `Express` `MongoDB` `Stripe` `React`

---

## Other Projects

**[OpsCore](https://github.com/stdmitry-aps/opscore)**
Small demo of an internal HR and operations platform -- the kind of thing I build in production but can't show. Multi-tenant RBAC where permissions are validated at import time so a misconfigured perm breaks the server on startup, not at 2am when someone triggers the wrong endpoint. AI assistant that runs as a Celery task (not a streaming response) so it finishes even if the client disconnects. Two-stage RAG: Qdrant for candidate retrieval, cross-encoder for reranking. Short-term agent memory in Redis, long-term in Postgres.
`Django REST` `Next.js 14` `PostgreSQL` `Redis` `Celery` `Qdrant` `Claude API`

**[Scheduler](https://github.com/stdmitry04/scheduler)**
World-agnostic stride scheduler for real-time agent simulations. Any world plugs in via a single DoAction interface. 4-tier priority system (CRITICAL/GAMEPLAY/ECONOMY/COSMETIC) with frame budgets and an async EventQueue for deferred actions. Scales to 50,000+ concurrent agents, compiled to WebAssembly via Emscripten.
`C++23` `WebAssembly` `Emscripten`

**[QuiKard](https://github.com/stdmitry04/quikard)**
Digital business card -- create in under a minute, export to Apple Wallet, share via NFC tap.
`Next.js 15` `FastAPI` `PostgreSQL` `Apple Wallet API`

**[Volunteer Matchmaker](https://github.com/stdmitry04/Volunteer_Matchmaker)**
Composite-scoring volunteer match system (proximity, skills, urgency, reliability) with Ethereum smart contracts for on-chain donation tracking. SpartaHack XI Blockchain Track 3rd Place.
`Next.js 15` `Django REST` `Solidity` `Gemini AI`

**[CourseChecker](https://github.com/neontap/spartahack)**
Course review aggregator -- only verified university students (school email) can submit. Tracks 5 rating dimensions per professor and semester.
`Next.js 14` `Supabase` `GPT-4` `TypeScript`

---

## Stack

**AI/ML:** RAG Systems - Vector Search (Qdrant) - LLM Tool Calling - Cross-encoder Reranking - Per-user Memory - Eval Design

**Backend:** Python - Django REST - FastAPI - Celery - Node.js - RBAC - Stripe

**Frontend:** TypeScript - React - Next.js - Tailwind CSS

**Infra:** AWS (ECS, RDS, S3) - Terraform - Docker - CI/CD - PostgreSQL - Redis

---

## Education

Michigan State University -- B.S. Computer Science, Business Minor - GPA 3.75 - May 2026

---

[LinkedIn](https://linkedin.com/in/stdmitry04) - starodu5@gmail.com