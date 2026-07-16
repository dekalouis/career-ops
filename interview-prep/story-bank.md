# Story Bank — Master STAR+R Stories

This file accumulates your best interview stories over time. Each evaluation (Block F) adds new stories here. Instead of memorizing 100 answers, maintain 5-10 deep stories that you can bend to answer almost any behavioral question.

## How it works

1. Every time `/career-ops oferta` generates Block F (Interview Plan), new STAR+R stories get appended here
2. Before your next interview, review this file — your stories are already organized by theme
3. The "Big Three" questions can be answered with stories from this bank:
   - "Tell me about yourself" → combine 2-3 stories into a narrative
   - "Tell me about your most impactful project" → pick your highest-impact story
   - "Tell me about a conflict you resolved" → find a story with a Reflection

## Stories

<!-- Stories will be added here as you evaluate offers -->
<!-- Format:
### [Theme] Story Title
**Source:** Report #NNN — Company — Role
**S (Situation):** ...
**T (Task):** ...
**A (Action):** ...
**R (Result):** ...
**Reflection:** What I learned / what I'd do differently
**Best for questions about:** [list of question types this story answers]
-->

### [Enterprise Deployment] QNB On-Premise Go-Live
**Source:** Report #058 — Mistral AI — Applied AI Engineer, Fullstack (EMEA)
**S (Situation):** Sokratech deploying fraud detection platform for QNB bank — production-critical, on-site, single-day window.
**T (Task):** Lead the full deployment: integration testing, UAT coordination, go-live, and staff training.
**A (Action):** Ran integration tests systematically, coordinated UAT sessions with bank IT, fixed blockers in real-time on-site.
**R (Result):** Fraud detection active in production by end of day; trained staff post go-live.
**Reflection:** Enterprise deployment is 30% technical and 70% trust-building under pressure. Next time I'd prepare a one-page "quick reference" card for staff training rather than improvising.
**Best for questions about:** client-facing delivery, working under pressure, stakeholder communication, enterprise deployment

### [Pre-Sales Engineering] OCBC Pre-Sales POC
**Source:** Report #058 — Mistral AI — Applied AI Engineer, Fullstack (EMEA)
**S (Situation):** Sokratech needed to win OCBC as a bank client; I had to build convincing POC features fast.
**T (Task):** Build alerts revamp, workflow UI, and case escalations in time for the sales evaluation.
**A (Action):** Prioritized visual impact + functional demo; built the workflow UI end-to-end in TypeScript/Next.js.
**R (Result):** POC completed and delivered for the pre-sales evaluation.
**Reflection:** I'd instrument the POC with real latency benchmarks from the start -- the "wow" moment would be stronger with data rather than approximations.
**Best for questions about:** pre-sales work, moving fast, building for non-engineers, prioritization

### [Enterprise Client Win] Saakuru Multi-Tenant Backend
**Source:** Report #058 — Mistral AI — Applied AI Engineer, Fullstack (EMEA)
**S (Situation):** Haircare enterprise client (9-figure valuation, HK) needed a full product suite in 4 weeks.
**T (Task):** Build multi-tenant NestJS backend: Shopify sync (300+ products, 5,000+ SKUs, 5,000 customers) + OpenSearch + BullMQ CDC pipeline + AWS S3/SQS.
**A (Action):** Designed multi-tenancy layer first, then built Shopify webhook handlers + BullMQ jobs for CDC; used OpenSearch for catalog search.
**R (Result):** Secured year-long contract; system in production.
**Reflection:** The 4-week deadline forced opinionated architecture choices. I'd document trade-offs more explicitly so the next engineer understands the reasoning.
**Best for questions about:** fast delivery, architecture decisions, working in small teams, client impact

### [AI Product] Imgsearch - CLIP Semantic Search
**Source:** Report #058 — Mistral AI — Applied AI Engineer, Fullstack (EMEA)
**S (Situation):** Google Drive has no semantic photo search; I wanted to find photos by describing what I remember.
**T (Task):** Build a production semantic photo search using vision-language models.
**A (Action):** FastAPI + pgvector backend on Railway; Modal GPU indexing with CLIP ViT-L/14; Next.js frontend with Clerk auth.
**R (Result):** Live at imgsearch.online -- describe a photo, retrieve it from Drive.
**Reflection:** Retrieval quality bottleneck is almost always indexing quality, not model choice. I'd invest more in the metadata strategy earlier next time.
**Best for questions about:** LLM/AI experience, side projects, building from scratch, vector search

### [Speed & Leverage] Saakuru 4-Week Full Launch
**Source:** Report #058 — Mistral AI — Applied AI Engineer, Fullstack (EMEA)
**S (Situation):** 4-person team, full product suite (NestJS backend + React admin + 2 Expo apps), 4-week hard deadline.
**T (Task):** Ship the entire backend (99+ DB tables) and coordinate frontend teams to hit the deadline.
**A (Action):** Cut scope to MVP on non-critical features; Dockerized dev env (onboarding 2 days to 4 hours); wrote API contracts up front.
**R (Result):** Full suite shipped on time; year-long contract secured.
**Reflection:** Speed came from removing coordination overhead, not from working faster. Dockerized env + API contracts are now week-1 actions for any new project.
**Best for questions about:** startup speed, team leadership, prioritization, technical decisions under pressure
