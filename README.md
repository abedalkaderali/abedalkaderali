# Hi, I'm Abedalkader Ali 👋

**AI Engineer & Full-Stack Software Engineer** · Production LLM Systems · .NET / Python / Laravel · React / SvelteKit

I build production AI systems — the kind that handle real customers, real money, and real operational consequences, not demos.

📍 Lebanon · 🗣️ Arabic (Native), English (C1) · 🌏 Working remotely with an Australian team

---

## 💼 Experience

**AI & Full-Stack Engineer** · iTrack Technologies (Melbourne, Australia — Remote) · *Jun 2026 – Present*
- AI **email-to-booking agent** on **AWS Bedrock + Anthropic Claude**: ingests freight emails with PDF/Word transport orders, extracts structured shipment data via tool calling, creates draft bookings — **200+ automated**, near-zero false positives
- Triage layer separating transport orders from arrival notices; loop-safe IMAP ingestion with a persistent seen-ledger for **exactly-once processing**; per-email token budgeting
- Human-in-the-loop React review UI — nothing commits unchecked
- **Provider-agnostic AI layer**: cloud and self-hosted OpenAI-compatible models swap via config, no rewrite
- Passwordless **carrier dispatch** with SHA-256-hashed scoped tokens, GPS capture, signature/photo Proof of Delivery → S3
- **Linehaul dual-rate pricing** with live margin across pricing, invoicing and job views
- Redesigned the **React Native (Expo) driver app** — floating tab navigation, signature-capture POD, in-app truck-route map (HERE tiles on MapLibre)
- Additive **zero-downtime schema migrations** against a live production database

**AI Engineer — LLM, Automation & Data Systems** · YMY Tutoring · *Feb 2026 – Sep 2026*
- Production **WhatsApp AI agent** (Laravel · Chatwoot · Anthropic Claude) handling order-taking and debt collection in Kuwaiti Arabic for paying customers
- Multi-flow LLM router with function calling across **25+ backend tools** — pricing, payment links, debt summaries, order creation, escalation
- Moved pricing, discounts and promo rules into a **deterministic business-logic layer outside the prompt**, eliminating LLM pricing errors in production
- Forced-reply safeguards, hallucination guard, **80+ test regression suite**, structured logging, critical-failure alerting
- Redis queue workers, multi-environment deployment, live production debugging

**Full-Stack Software Engineer** · noblesdigital · *Jan 2025 – Jan 2026*
- SvelteKit + Supabase apps with secure auth, real-time data, RBAC — **5,000+ monthly users**
- Schema-driven validation with Superforms + Valibot; **95+ Lighthouse scores**

**Backend Developer** · BotlerAI · *Jan 2024 – Dec 2024*
- Django/Flask REST APIs — **30% faster** response times
- Microservices with Docker and Kubernetes; CI/CD with automated testing; JWT/OAuth; AWS and DigitalOcean

---

## 🛠️ Featured Projects

**AI Executive Secretary** — WhatsApp-native automation platform
**29 orchestrated n8n workflows (367 nodes)** · GPT-4o · PostgreSQL · Docker · WhatsApp Cloud API · Google Workspace
Code-enforced human-in-the-loop approval gate — sensitive actions require an exact approval ID matched against the raw message, making it **structurally impossible for the LLM to authorise its own action** (validated with adversarial tests). SHA-256 payload hashing invalidates an approval if content changes; an idempotency ledger prevents duplicate sends on retry. HMAC-SHA256 webhook verification, phone allow-listing, OAuth 2.0, full audit trail. Isolated per-client PostgreSQL + n8n stacks.

**ORCA** — SvelteKit · Svelte 5 · Supabase
Inventory and sales system covering categories, items, suppliers, stock and orders, with schema-driven validation and reusable form components.

**CarCare** — Flutter · Django · PostgreSQL
Vehicle maintenance platform with automated reminders driven by mileage and installation dates.

---

## 🧰 Tech Stack

**AI & LLMs** AWS Bedrock · Anthropic Claude · OpenAI · Self-Hosted LLMs (Ollama / Qwen2.5) · Function & Tool Calling · Structured Outputs · Multimodal Vision · LLM Agents · RAG & Vector Databases · Prompt Engineering · LLM Guardrails · Human-in-the-Loop Systems · n8n

**Backend** C# · ASP.NET Core / .NET 9 · Python · Django · DRF · Flask · FastAPI · Laravel (PHP) · Node.js · REST API Design · JWT / OAuth2 · Microservices

**Frontend** React · TypeScript · React Native (Expo) · SvelteKit · Svelte 5 · Tailwind CSS

**Data & Integration** PostgreSQL · MySQL · MongoDB · Redis · Supabase · AWS S3 · IMAP · PdfPig · OpenXML · WhatsApp Cloud API · Google Workspace APIs · HERE Maps · MapLibre

**Cloud, Security & DevOps** AWS · Docker · Kubernetes · CI/CD · GitHub Actions · Nginx/TLS · HMAC-SHA256 · SHA-256 Token Hashing · Scoped Tokens · Idempotency · RBAC · Audit Logging

---

## 🎓 Education & Certifications

**B.E. in Computer Engineering** — Lebanese International University · 2018 – 2024

- **AI-Assisted Coding, Professional Certificate** — American University of Beirut (AUB), MSFEA · 2026
- **The AI Engineer Path** — Scrimba, 14-week intensive · Nov 2025
- **AI Automation: LLM Apps & AI Agents with n8n & APIs** — Udemy · Jul 2026
- **n8n: AI Agents, Automations & Voice Agents** — Udemy, 59 hrs · Dec 2025
- Master Svelte 5 & SvelteKit · Advanced JavaScript (Scrimba) · Fullstack Bootcamp · Flutter/Firebase
- **Foundations of Computer Science** — SE Factory / Abdulla Al Ghurair Foundation

I also teach an introductory Java programming course at university level.

---

## 📫 Contact

📧 abedalkader.M.A@outlook.com · 💼 [LinkedIn](https://www.linkedin.com/in/abedalkaderali) · 🌐 [atsdigitals.com](https://www.atsdigitals.com)
