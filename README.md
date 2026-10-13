### Ade Nur Hidayat

**Founder & Lead Engineer — [PT ArvaTech Solusi Digital](https://arvatech.id)** · Indonesia (GMT+7)

I design, build and operate production software end to end: backend services, web and mobile
apps, and AI-powered products. Most of what I ship is multi-tenant platforms a real operations
team uses every day — placement systems, marketplaces, point of sale, and document-intelligence
pipelines.

#### What I'm working on

- **Wiyata — student placement platform.** Moves Indonesian university students into Japanese
  companies (Kenshusei / CoE programme): job distribution, applications, selection pipeline,
  CoE document generation, post-arrival evaluation.
  `Next.js` · `tRPC` · `Drizzle` · `PostgreSQL`
- **Indah Mall — B2B wholesale marketplace.** Seller-scoped catalogue, guest and member checkout,
  payment lifecycle, wallet and affiliate flows — storefront, admin console and mobile app over a
  single schema. `FastAPI` · `async SQLAlchemy` · `PostgreSQL` · `Redis` · `Cloudflare R2`
- **[GarasiMini](https://garasimini.id) — diecast catalogue with visual search.** Photo-based item
  matching (CLIP embeddings + `pgvector`), batch media pipeline, mobile client.
  `Go` · `PostgreSQL` · `Flutter`

#### Selected systems

- **[POS ArvaTech](https://pos.arvatech.id)** — point of sale for a coffee franchise: cashier flow,
  per-branch menus and pricing, customer loyalty, ingredient inventory, business reporting.
  `Next.js` · `PostgreSQL`
- **[JagatLabs](https://www.jagatlabs.com)** — AI content platform (image, video, audio) with
  multi-provider routing, admin console and pay-as-you-go billing. `FastAPI` · `Next.js`
- **[HadirQ](https://hadirq.arvatech.id)** — QR attendance for schools: multi-tenant, classes and
  teachers, live reporting. `Next.js` · `Supabase` · `PostgreSQL`
- **[Tripzi](https://tripzi.io)** — travel-sharing product: API, web app and mobile client with
  email/Google auth and deep links. `FastAPI` · `React` · `Flutter`
- **ARTeX** — autonomous penetration-testing console: agent orchestration, scan and traffic
  recording, report generation, bring-your-own LLM profiles. `Go` · `Next.js` · `Docker` (AGPL-3.0)
- **Enterprise RAG Engine** — regulatory document intelligence with a strict four-level taxonomy
  and hybrid retrieval. `Quarkus` · `Java 21` · `PostgreSQL`
- **Wilayah API** — REST API for Indonesian administrative regions (Kemendagri codes) with
  formatted full-hierarchy addresses.

#### Toolbox

- **Backend** — Python (FastAPI), TypeScript/Node, Go, Java (Quarkus · Spring)
- **Frontend** — React, Next.js, TanStack, Tailwind CSS, Flutter
- **Data** — PostgreSQL (+ `pgvector`), Redis, Supabase, SQLAlchemy, Drizzle, Prisma, Alembic
- **Infra & AI** — Docker, GitHub Actions, VPS/EasyPanel, Cloudflare R2, RAG and LLM integration

#### How I work

- Typed contracts at the boundaries, migrations under version control, tests that run in CI
  before anything reaches production.
- A merge is not a release: every deploy is verified against the running system, not assumed.
- Boring, well-understood technology that the next engineer can pick up without a handover call.

#### Get in touch

- Products, consulting and engineering partnerships: **[arvatech.id](https://arvatech.id)**
- Most customer work lives in private repositories (client code). Happy to walk through
  architecture, trade-offs and code on a call.
