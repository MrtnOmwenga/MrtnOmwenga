### Hi, I'm Martin 👋

Fullstack & platform engineer in Nairobi (GMT+3). I build backend systems and the infrastructure that ships them, currently as tech lead at a small company delivering platforms for European clients.

**What I work on**

- **Backend:** Node.js / TypeScript (NestJS, Express), Go, REST & GraphQL APIs, Kafka and BullMQ workers, PostgreSQL & MongoDB
- **Platform:** Kubernetes, Terraform, Docker, GitHub Actions, GitOps with Flux, AWS (Solutions Architect – Associate), Google Cloud (Cloud Run), DigitalOcean, Cloudflare (Workers)
- **Security:** secrets management (Infisical), signed images and SBOMs (cosign), restricted Pod Security and network policies, PostgreSQL row-level security, applied cryptography (end-to-end encryption, signatures, Merkle-tree logs)
- **Integrations & AI:** two-way ERP sync (Sage), RAG pipelines and agent loops on OpenAI embeddings, Claude Code hooks
- **Quality:** Jest unit & e2e suites, Playwright, property-based and mutation testing; Sentry and Grafana for observability

**Selected projects**

| Project | What it is |
|---|---|
| [lighthouse](https://github.com/MrtnOmwenga/lighthouse) | My portfolio as a live broadsheet, published by the uptime monitor that watches it and its demos. Go, PostgreSQL row-level security, cookieless analytics, a Vue sandbox console. Runs on Google Cloud Run behind a Cloudflare Worker, provisioned with Terraform, with keyless deploys and cosign-signed images; also packaged for Kubernetes (Kustomize, Flux, restricted Pod Security) and validated on a local cluster |
| [RBAC-API](https://github.com/MrtnOmwenga/RBAC-API) | Multi-tenant access control: policy as data, PostgreSQL row-level security, hash-chained audit log, and *Redacted*, a live collaborative editor where classified words black out as you type, re-authorized on every keystroke (Yjs). 605 tests, including a generated authorization matrix and Playwright leak tests; 100% mutation score on the security-critical modules. NestJS, PostgreSQL |
| [GhostChat](https://github.com/MrtnOmwenga/GhostChat) | End-to-end encrypted chat: messages and files encrypted in the browser (libsodium), signed hash-chained history the server can't alter unnoticed, and a key transparency log with Merkle proofs. React, Express, Socket.IO, MongoDB, Redis; Jest + Playwright |
| [offline-driver](https://github.com/MrtnOmwenga/offline-driver) | Offline-first writes and reads for React Native: a durable outbox that tells a dropped connection from a rejected request, and a synchronous Expo SQLite layer. Generalised from a production app's offline layer. TypeScript; property-based tests |
| [living-docs](https://github.com/MrtnOmwenga/living-docs) | Project docs that keep themselves up to date: Claude Code hooks file each session's decisions into a shared docs repo, linted before push, with changes of purpose routed to human review. A standalone version of a pipeline I designed at work |
| [pair-bridge](https://github.com/MrtnOmwenga/pair-bridge) | Two-way file sharing between a Linux laptop and an Android tablet: FastAPI + FUSE on the laptop, a native Android DocumentsProvider on the tablet |

**Recent work (private client code)**

- Per-PR preview environments: every backend pull request gets its own Kubernetes namespace and URL, torn down when the PR closes
- Two-way batch sync between a B2B ordering platform and a Sage ERP, with retries, status logging and freshness alerts
- Node.js/Kafka microservices handling 10,000+ requests per minute, with schema design for scale
- A production AI assistant: agent loop with tool use, retrieval, and queued model calls, delivered as a Telegram bot

**Contact:** omwenga.mrtn@gmail.com · [LinkedIn](https://www.linkedin.com/in/omwenga-martin)
