# Hi, I'm Kanishk 👋

Backend and distributed systems engineer. I recently finished my **M.S. in Computer Science at NYU** (May 2026). Before that I spent two years as a **Software Engineer at ZS Associates**, building data backends for pharma clients like J&J, Pfizer, Merck and Lilly.

I like systems that are fast, measurable, and survive failure. Most of my projects end with a load test, a failover drill, or a Prometheus dashboard.

📍 New York, NY · 🌐 [kanishkaggarwal.com](https://kanishkaggarwal.com) · 💼 [LinkedIn](https://linkedin.com/in/kanishkaggarwal1) · ✉️ ka3506@nyu.edu

---

## 🔨 Featured projects

### [DistKV](#) — distributed key-value store · `C++20` `gRPC` `AWS` `Terraform`
A Redis-protocol key-value store built from scratch, compatible with `redis-cli` and `memtier_benchmark`.
- Sharded across 6 nodes with consistent hashing and live key migration
- Primary-backup replication over gRPC with heartbeat-based failover
- **150,000 ops/sec at 1.8 ms p99** across 3 AWS availability zones
- Killed primaries under load: **zero acknowledged writes lost**, 3 s failover

### [ShiftStack](#) — automated Flask → FastAPI migration · `Python AST` `Celery` `Redis` `FastAPI` `Ollama`
Static analysis that plans and ships a framework migration for you.
- Parses Flask codebases into ASTs, builds a cross-file dependency graph, and risk-scores every route
- Generates migration patches with LLM-written explanations and opens the PRs on GitHub
- Async Celery jobs with progress, retries and cancellation; GitHub OAuth with AES-encrypted tokens

### [Music Intelligence](#) — recommendation service · `PostgreSQL` `scikit-learn` `Docker` `Prometheus`
Playlist recommendations from 19,000+ songs of Spotify listening history.
- Sparse-matrix rewrite of the TF-IDF + KNN pipeline: **~60% less memory, 10x faster** playlist generation
- Served **28,000+ requests** in production on Render with health probes and Prometheus metrics
- 138-test GitHub Actions pipeline on every deploy; schema evolved through 7 Alembic migrations

### [AI Search Engine](#) — RAG answer engine · `Redis` `SQLite` `Gemini`
- Continuously ingests from NewsAPI, RSS and the open web; ranks sources on similarity, recency, credibility and diversity
- 3-tier cache (Redis → SQLite → live fetch) cut repeat-query latency from **~1 s to under 10 ms**

---

## 🧰 Tech stack

**Languages:** Python · SQL · C++ · TypeScript · JavaScript
**Backend:** FastAPI · Flask · gRPC · REST · Celery · asyncio · OAuth2/JWT · Pydantic
**Data:** PostgreSQL · Redis · SQLAlchemy · Alembic
**Infra:** Docker · AWS (EC2, S3) · Terraform · GitHub Actions · Prometheus · Linux
**AI/ML:** RAG · LangChain · OpenAI / Gemini / Ollama APIs · scikit-learn · TensorFlow · Pandas
**Frontend:** React · Next.js

---

## 🎯 Right now

Looking for **backend, infrastructure, or distributed systems** roles. Happy to talk about consistent hashing, cache design, or why your ingestion job takes three days.
