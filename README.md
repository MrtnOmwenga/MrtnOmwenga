### Hi, I'm Martin 👋

Fullstack & platform engineer in Nairobi (GMT+3). I build backend systems and the infrastructure that ships them, currently as tech lead at a small company delivering platforms for European clients.

**What I work on**

- **Backend:** Node.js / TypeScript (NestJS, Express), REST & GraphQL APIs, Kafka and BullMQ workers, PostgreSQL & MongoDB
- **Platform:** Kubernetes, Terraform, Docker, GitHub Actions CI/CD, AWS (Solutions Architect – Associate), DigitalOcean, secrets management (Infisical)
- **Integrations & AI:** two-way ERP sync (Sage), RAG pipelines and agent loops on OpenAI embeddings
- **Quality & security:** Jest unit & e2e suites, Playwright E2E with parallel, isolated workers; Sentry and Grafana for observability; applied cryptography (end-to-end encryption, signatures, Merkle-tree logs) in GhostChat

**Recent work (private client code, public write-ups coming)**

- Per-PR preview environments: every backend pull request gets its own Kubernetes namespace and URL, torn down when the PR closes
- Two-way batch sync between a B2B ordering platform and a Sage ERP, with retries, status logging and freshness alerts
- Node.js/Kafka microservices handling 10,000+ requests per minute, with schema design for scale
- A production AI assistant: agent loop with tool use, retrieval, and queued model calls, delivered as a Telegram bot

**Selected public projects**

| Project | What it is |
|---|---|
| [GhostChat](https://github.com/MrtnOmwenga/GhostChat) | End-to-end encrypted chat: messages and files encrypted in the browser (libsodium), signed hash-chained history the server can't alter unnoticed, and a key transparency log with Merkle proofs. React, Express, Socket.IO, MongoDB, Redis; Jest + Playwright |
| [pair-bridge](https://github.com/MrtnOmwenga/pair-bridge) | Two-way file sharing between a Linux laptop and an Android tablet: FastAPI + FUSE on the laptop, a native Android DocumentsProvider on the tablet |
| [incident-tracking](https://github.com/MrtnOmwenga/incident-tracking) | Incident tracker with a Go backend, PostgreSQL migrations, Docker Compose and a Jenkins pipeline |
| [TypeScript-REST-API](https://github.com/MrtnOmwenga/TypeScript-REST-API) | Typed REST API with request validation, Swagger docs and Jest tests |
| [RBAC-API](https://github.com/MrtnOmwenga/RBAC-API) | Multi-tenant access control: policy as data, PostgreSQL row-level security, document sharing, clearance-classified words, hash-chained audit log, and *Redacted*, a live demo where words black out while you type (Yjs collaboration re-authorized on every permission change). 600+ tests incl. a generated authorization matrix and 100% mutation score. NestJS, PostgreSQL, Testcontainers, Playwright |

**Contact:** omwenga.mrtn@gmail.com · [LinkedIn](https://www.linkedin.com/in/omwenga-martin)
