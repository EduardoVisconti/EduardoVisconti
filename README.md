## Eduardo Visconti

**AI Engineer · Full-Stack.** Tampa, FL.

I build production systems where an LLM agent is part of the runtime, not a demo bolted to
the side of one, and the apps people use them in.

**Now:** AI Developer at United Financial Resources since April 2026. I built the company's
deed retrieval service from scratch and own it, and I lead the frontend of AI Hub, our
internal multi-agent chat platform.

---

### Selected work

**Deed retrieval platform** · private

Built to replace a deed lookup that takes someone 10 to 30 minutes by hand. Given an owner
and a county, it finds the county's records portal, logs in, runs the search, checks the PDF
and returns the deed to AI Hub or the company CRM. Integrations for 70+ records-portal
platforms, 840+ counties set up for automated search, 60 architecture decision records, and
7,500+ tests run inside the shipped image on every pull request. When a portal breaks, an
agent capped by iterations diagnoses it and proposes a fix, and a person approves any change
to a county's validation or retrieval settings.

**AI Hub** · internal

The company's internal multi-agent chat platform, used by about 60 employees. I lead the
frontend (Next.js 16, React 19, TypeScript): I redesigned the whole interface on my own,
fixed a streaming race that lost or merged up to 75% of agent replies, and wrote the MCP
server that lets its agents search for deeds.

**Forja** · [app.forjahybrid.com](https://app.forjahybrid.com) · [case study](https://github.com/EduardoVisconti/forja-case-study) · [open TestFlight beta](https://testflight.apple.com/join/bRREz5sS)

A training app for people who mix lifting, HYROX, functional work and running: workouts,
cardio, programs, habits, body weight and progress in one app, with the whole workout on one
screen like a spreadsheet. The phone holds the data and syncs to Supabase in the background,
so it works with no connection. Built solo with 5,000+ tests. React Native, Expo, TypeScript.

**ConsciencIA** · client work

A private journaling app where a psychology practice's patients get AI feedback on what they
write. Entries are encrypted at rest, consent is given item by item, and the AI key never
reaches the browser. Astro, PHP, MySQL.

**Psychology practice site** · client work

The website and course sales pages for a clinical psychologist: a static Astro build for a
shared host with no Node, and a PHP lead form with a honeypot, an origin check, dedup and two
rate limits.

**AssetOps** · [live demo](https://asset-ops.vercel.app/login) · [repo](https://github.com/EduardoVisconti/AssetOps)

Equipment management with role-based access, maintenance scheduling and an append-only audit log.
Next.js, TypeScript, Firebase.

**LeadFlow** · [repo](https://github.com/EduardoVisconti/leadflow)

CRM for an electronics reseller: Kanban pipeline, contacts, product catalog and AI deal
analysis. Next.js, TypeScript, Supabase, Gemini.

---

### Stack

**Languages:** Python · TypeScript · SQL

**Backend:** FastAPI · asyncio · PostgreSQL (row-level security) · NATS JetStream · Playwright · pytest

**Frontend:** React · React Native (Expo) · Next.js · Tailwind

**AI:** LLM agents and tool calling · MCP · LiteLLM with self-hosted models

**Infra:** Docker · GitHub Actions · Vercel · Supabase

---

[Portfolio](https://eduardo-visconti.vercel.app) · [LinkedIn](https://www.linkedin.com/in/eduardo-visconti/)
