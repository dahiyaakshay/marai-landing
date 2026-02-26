# MarAI

MarAI is a full-stack AI-powered marketing platform designed for real-world, multi-client marketing execution.

Built with modern web technologies and direct LLM integrations, MarAI unifies content generation, SEO optimization, brand visibility tracking, and campaign management into a single, scalable system.

This is not a single purpose AI tool.

It is a unified AI-native MarTech platform.

---

## 🚀 What MarAI Does

MarAI streamlines marketing workflows by integrating:

- AI-powered content generation
- Multi-client management
- SEO & GEO content optimization
- AI brand citation tracking
- Campaign calendar planning
- Export ready asset management
- Business intelligence dashboards

The platform reduces execution time across marketing workflows by up to 80% while preserving brand context and quality.

---

## 🧠 Dual AI Architecture

MarAI integrates two AI systems with distinct responsibilities:

### 1️⃣ Google Gemini 2.5 Flash
- Primary content generation engine
- Context-aware prompts with client injection
- 50K token conversation handling
- Token usage monitoring with threshold warnings

### 2️⃣ Perplexity AI (Sonar Pro)
- AI citation tracking
- Brand visibility scoring (0–100)
- Share-of-voice analysis vs competitors
- Citation extraction & reporting

This dual-AI strategy separates content creation from intelligence tracking eliminating single model dependency.

---

## 🏗 Modern Full-Stack Architecture

### Frontend
- React 18 + TypeScript (strict mode)
- Vite build pipeline
- Custom CSS theme system (~2,900 lines)
- 14 page components
- Modular hooks & state persistence

### Backend
- Node.js 18+ / Express 4.18
- PostgreSQL 16 with connection pooling
- Opaque token authentication (SHA-256 hashed)
- 10 modular service layers
- 55+ RESTful endpoints
- Rate limiting + Helmet security
- Google OAuth integration (Search Console + GA4)

### Database
- 11 migrations
- Multi-tenant client scoping
- 10 asset types
- Optimized indexing + integrity constraints

Total codebase:
~40,000+ lines across frontend & backend.

---

## 🧩 Platform Modules (14+ Integrated Tools)

### General
- Real-time KPI Dashboard

### Calendars
- Marketing Calendar
- Social Media Calendar
- Email Campaign Calendar

### Core Tools
- Content Creator (12+ content types)
- Content Gap Analyzer
- Keyword Research
- Persona Builder
- SEO Strategy Generator
- Content Optimizer (SEO + GEO scoring)
- Citations Tool (AI visibility tracking)

### Library
- 100-item asset capacity
- 10 saveable asset types
- One-click reuse & export

---

## 🔐 Security & Authentication

MarAI uses opaque token authentication instead of JWT.

Why?

- Instant token revocation
- No sensitive payload inside tokens
- Database validated sessions
- Multi-session support (up to 10 per user)

Security includes:

- bcrypt password hashing (12 rounds)
- SHA-256 token hashing
- Email verification & reset workflows
- Rate limiting
- SQL injection prevention
- Secure API key storage
- User data isolation per client

Designed for enterprise grade marketing environments.

---

## 📤 Multi-Format Export System

Client-side export generation supports:

- PDF (styled client-ready reports)
- Excel (structured data exports)
- Word (formatted documents)

Exports available for:

- Citation reports
- SEO/GEO optimization reports
- Calendars
- Personas
- Keyword research
- Content gap analysis

No server roundtrip required.

---

## 📊 Client Scoped Intelligence

MarAI supports structured multi-client management:

- Client profiles (industry, goals, brand guidelines)
- Context-aware AI outputs
- Client scoped content storage
- Timestamped content history
- Business intelligence dashboard
- Cross client analytics

Each output is linked via `client_id` for full separation.

---

## ⚙️ Engineering Highlights

- 10 backend services (modular & extensible)
- Session persistence across 9 tool types
- 50K token management with visual thresholds
- Google OAuth integration (SC + GA4)
- Web scraping via Puppeteer + Cheerio
- Export service (~1,700+ lines)
- Modular route structure (8 route files)

This is production grade marketing infrastructure.

---

## 📈 Competitive Advantages

MarAI differentiates itself by:

- Dual AI integration (Gemini + Perplexity)
- AI citation visibility tracking
- SEO + GEO optimization engine
- Multi-client native support
- Session persistence across workflows
- Multi-format export pipeline
- Opaque token authentication (more secure than JWT)
- Fully self-contained architecture

It combines marketing strategy with real engineering depth.

---

## 🧭 Positioning

MarAI operates at the intersection of:

- AI-powered marketing automation
- LLM-native content systems
- AI brand visibility tracking
- Multi-client MarTech infrastructure
- Secure, scalable web application architecture

It is designed for agencies, consultants, and marketing teams working in the AI era.

---

## 📁 Repository Contents

This repository contains the presentation and portfolio representation of MarAI.

Production backend and full SaaS deployment remain private.

---

## 👤 Developer

Built and designed by **Akshay**

Focused on AI-native marketing infrastructure, retrieval engineering, and scalable full-stack systems.
