<h1 align="center">Hi, I'm Lev 👋</h1>

<p align="center">
  <b>Go backend developer</b><br>
  🟢 <b>Open to work</b>
</p>

<p align="center">
  🇬🇧 English · 🇷🇺 Русский
</p>

<p align="center">
  <a href="https://t.me/undndnwnkk"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:bykov.lev74@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/lev-bykov-505a532b9"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## About

I build backend services in Go and like results I can measure: query plans, indexes, caching, queues, tests in CI.
For a year I worked full-time at an online programming school on a microservices platform with 600 students and 60 RPS at peak.
Now I'm finishing my bachelor's at ITMO University.

## Experience

**Go Backend Developer · Innoprog** (online programming school) · Aug 2025 – Oct 2026
Product team of 7–8 people. Owned the KPI, notifications, schedule and browser-IDE modules from design to release.

| Area | Result | How |
|---|---|---|
| Schedule API | p95 **420 → 150 ms**, PostgreSQL load **−25%** | `EXPLAIN ANALYZE`, composite indexes, Redis cache with invalidation |
| Notifications | Telegram delivery **96% → 99.5%**, send latency **~3× lower** | RabbitMQ, retries with exponential backoff, status tracking, deduplication |
| Browser IDE | p95 sync latency **300 → 100 ms** | WebSocket broadcast optimization, cursor event throttling |
| KPI payouts | Bonus preparation for 20 teachers **1.5 h → 15–20 min** | Event-driven KPI calculation, PostgreSQL aggregation |
| AI assistant | Time to first chunk **2.4 → 1 s** | Streaming LLM API responses, timeouts, error handling |

## Projects

| Project | What it is |
|---|---|
| [**go-vk-messenger**](https://github.com/undndnwnkk/go-vk-messenger) | Messenger backend: direct and group chats, multi-device WebSocket delivery, cursor pagination, search, reactions, unread counters. Runs on 2 Kubernetes replicas with Redis Pub/Sub and a shared sliding-window rate limit. Prometheus + Grafana, 74.4% coverage, CI on GitHub Actions. Passed a VK Education mentor review. |
| [**go-warehouse-system**](https://github.com/undndnwnkk/go-warehouse-system) | Order processing across 4 Go services (auth, order, warehouse, notification): gRPC for stock reservation, Kafka for events, JWT auth. Load-tested at 500/500 successful orders with lossless event delivery. |
| [**go-pulse**](https://github.com/undndnwnkk/go-pulse) | Concurrent TCP scanner: worker pool, RPS limiting, retries, live stats, graceful shutdown. Benchmarked and profiled with built-in pprof. |
| [**go-mini-git**](https://github.com/undndnwnkk/go-mini-git) | Git-inspired version control: content-addressed snapshots, diff and restore, CLI and HTTP API with middleware, layered config, graceful shutdown. |

## Tech stack

| | |
|---|---|
| **Languages** | Go · SQL · Python · Java · C++ |
| **Backend** | chi · Gin · REST · gRPC · WebSocket · JWT · OpenAPI · microservices |
| **Data & queues** | PostgreSQL (pgx) · Redis · Kafka · RabbitMQ · MongoDB · ClickHouse |
| **Infra** | Docker · Kubernetes · GitHub Actions · GitLab CI/CD · Linux |
| **Observability** | Prometheus · Grafana · pprof · slog |
| **Testing** | go test (unit, integration, race detector) · Postman |
| **Tools** | Git · goose · golang-migrate · Claude Code · Codex · Cursor |

## Education

- **ITMO University**: BSc, Systems and Application Software (2024 – 2028)
- **VK Education**: Algorithms and Data Structures · Web Services Development in Golang · DevOps/SRE Engineer

**Languages:** Russian (native), English (B2)
