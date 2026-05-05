<div align="center">

# Sayan Das
### Full Stack Developer · TypeScript · React · Node.js

I ship production systems — real-time, multi-tenant, AI-powered — that solve problems people actually have.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sayandas24)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://sayanthisis.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sayandas.workmail@gmail.com)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/sayandas24)

**3 production apps shipped · 7 months · 1st place tech fest · Top 10 at Jadavpur University IIC Challenge**

</div>

---

## What I build

Full stack systems with a frontend-first mindset — real-time sync, multi-tenant architecture, offline-first data, AI integrations. I own features end-to-end: UI, API design, database schema, and deployment. No handoffs.

**Core stack:** TypeScript · React · Next.js · TanStack · Node.js · Express · MySQL · MongoDB · Redis · WebSockets · Docker

---

## Projects

---

### 🏆 Delycia — Multi-Tenant Restaurant Management SaaS
> **1st place, Brain Maniac Tech Fest 2025** (70+ teams) · **Top 10, IIC Prototype Challenge 2025** (120+ submissions, Jadavpur University)

Small restaurants in India run on pen-paper orders, WhatsApp menus, and manual billing. Delycia replaces all of it.

**Three apps, one backend:**
- **Customers** — scan QR code → browse menu → place order → track it live
- **Staff** — see incoming orders in real-time → update kitchen status → manage tables
- **Owners** — dashboard analytics, CRM, inventory, subscriptions, multi-restaurant management

**What I engineered:**

- **25% faster order processing** — optimized data handling and streamlined kitchen-to-waiter communication via WebSockets
- **Zero paper errors** — QR-enabled ordering with live Socket.IO order status pushed to kitchen and waiter screens simultaneously
- **Multi-device auth without friction** — built a `withAuth()` BFF wrapper that detects expired tokens, refreshes them, and retries the original request transparently. User never notices.
- **Concurrent refresh deduplication** — built a `RefreshCoordinator` singleton: if 5 API calls fail at once due to expired token, exactly 1 refresh fires — not 5
- **Redis caching layer** — token caching (5s TTL) cut backend auth load ~80%. Designed with graceful degradation: if Redis goes down, the app keeps running
- **Zero schema changes to onboard new restaurants** — multi-tenant architecture scoped every query by `restaurant_id` from day one
- **8 roles, 3 apps, 1 backend** — role-based access from Customer to SuperAdmin, all sharing one Express API

`TanStack Start` `TanStack Query` `Zustand` `Tailwind CSS` `Radix UI` `Node.js` `Express` `MariaDB` `Redis` `Socket.IO` `JWT` `Docker` `Hostinger VPS`

---

### 🤖 AI Interview Prep & Resume Generator
> Upload resume + job description → ranked preparation roadmap in under 30 seconds

- **100% valid AI output** — enforced strict schema on every Google Gemini API call, zero malformed responses
- **Hours → 30 seconds** — automated resume parsing, skill mapping, and gap analysis end-to-end
- **ATS-optimized resume generation** — JWT-secured, user-isolated REST APIs, zero data leakage between accounts

`React` `TypeScript` `Tailwind CSS` `Node.js` `Google Gemini API` `MongoDB` `Puppeteer` `JWT`

---

### 💊 Pharmacy Inventory & POS System
> Offline-first pharmacy management with barcode scanning and multi-branch ops

- **99% uptime during network outages** — offline-first sync layer via PowerSync eliminated single points of failure
- **Medicine lookup under 2 seconds** — camera-based barcode scanning replaced slow manual search
- **Expiry loss prevention** — automated stock alerts at 15, 30, and 90-day thresholds
- Multi-branch operations, role-based access, POS billing, and sales analytics from one deployment

`Next.js` `React` `TypeScript` `Supabase` `PowerSync` `Kysely` `Tailwind CSS` `Recharts`

---

## Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React · Next.js · TanStack Start · TanStack Query · TypeScript · Tailwind CSS · Zustand · Redux · Radix UI |
| **Backend** | Node.js · Express.js · REST API · WebSockets · Socket.IO |
| **Database** | MySQL · MariaDB · MongoDB · Redis · Supabase |
| **Auth & Security** | JWT · httpOnly cookies · CSRF protection · bcrypt · Rate limiting |
| **AI & Integrations** | Google Gemini API · Puppeteer · Twilio · PowerSync |
| **DevOps & Tools** | Docker · Docker Compose · VPS deployment · Vercel · Git |

---

## Achievements

🥇 **1st Place — Brain Maniac Tech Fest 2025** · Built Delycia (multi-tenant restaurant SaaS) · ranked 1st among 70+ teams

🏅 **Top 10 — IIC Prototype Innovation to Entrepreneurship Challenge 2025** · 30 finalists from 120+ submissions · organized by IIC & National Council of Education, Bengal · Jadavpur University


## Currently

- 🎓 3rd year B.Tech CSE · Camellia Institute of Engineering and Technology (MAKAUT)
- 🔍 Open to **full-time and internship roles** in full stack / frontend development
- 🚀 Building production systems that solve real problems — shipping weekly
- 🧠 Going deeper on system design, distributed systems, and DevOps

---

<div align="center">

**Let's build something that matters.**

[sayandas.workmail@gmail.com](mailto:sayandas.workmail@gmail.com) · [linkedin.com/in/sayandas24](https://linkedin.com/in/sayandas24) · [sayanthisis.vercel.app](https://sayanthisis.vercel.app/)

</div>
