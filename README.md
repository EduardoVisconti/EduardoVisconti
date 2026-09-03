## Eduardo Visconti

**Full-stack engineer · production AI systems.** Tampa, FL.

I build systems where an LLM agent is part of the runtime, not a demo — with budget
ceilings, human approval gates, failure classification, and self-healing when an
upstream source changes shape underneath it.

**Now** — AI Engineer @ United Financial Resources, since April 2026. Automated
property-deed retrieval across 3,000+ US counties (Python · FastAPI · PostgreSQL,
with an autonomous agent layer), and the tooling that exposes it as an agent
capability inside our internal AI Hub (Next.js · TypeScript).

---

### Selected work

**Forja** — [app.forjahybrid.com](https://app.forjahybrid.com) · iOS TestFlight

Offline-first hybrid-training app: guided strength sessions, cardio logging, daily
habit protocol, progress history. The device is the source of truth and the server
reconciles in the background, so the app stays fully usable with no connection.
React Native (Expo SDK 54), TypeScript strict, Supabase Postgres with row-level
security. Sole engineer.

**Deed retrieval platform** — private

Automated retrieval of property deeds across 3,000+ US counties, each of which
records on a different vendor portal. An agent layer keeps that integration fleet
working as portals change, under hard budget caps and a human approval gate.
Sole engineer — more test code than source, decisions recorded as ADRs, security
gates on every PR.

**AI Hub** — internal

The multi-agent platform several departments run on. I build the client: Next.js
and React 19, a custom NDJSON streaming protocol, the state architecture and the
artifact rendering layer, against a Python/FastAPI/Agno backend with role-based
access and a retrieval pipeline. 32 pull requests, shipped through review by three
other engineers, against a suite of 1,300 unit and ~200 end-to-end tests.

**Sueli Repulho** — [suelirepulho.com.br](https://suelirepulho.com.br)

Institutional site and sales pages for a psychology practice, with the paid-course
area delegated to an external platform. Astro, SEO- and mobile-first, shipped under
tight shared-hosting constraints that drove the whole architecture.

**LeadFlow** — [live](https://leadflow-electronics.vercel.app) · [repo](https://github.com/EduardoVisconti/leadflow)

CRM for an electronics reseller — Kanban pipeline, contacts, product catalog, and AI
deal analysis. Next.js · TypeScript · Supabase · Gemini.

---

### Stack

**Languages** — Python · TypeScript · SQL (PL/pgSQL)

**Backend** — FastAPI · asyncio · PostgreSQL (RLS) · Playwright · pytest

**Frontend** — React · React Native (Expo) · Next.js · Tailwind

**AI** — Anthropic & OpenAI tool-use · MCP · RAG with RBAC · budget and approval control

**Infra** — Docker · GitHub Actions · Vercel · Supabase

---

[LinkedIn](https://www.linkedin.com/in/eduardo-visconti/) · [Portfolio](https://eduardo-visconti.vercel.app)
