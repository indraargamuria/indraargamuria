<h1 align="center">Hi there! 👋 I'm Indra Arga Muria</h1>

<p align="center">
  <em>Passionate about building clean, efficient software that solves real-world problems.</em><br>
  <em>Deep roots in enterprise systems, moving fast with modern web tech.</em>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="200" alt="Cat Coding"/>
</p>

---

### 💡 About Me

- 🏢 **7+ years** working with Epicor ERP as a technical consultant — understand real business processes end-to-end
- 💻 Crafting clean, efficient code across full-stack (Python, TypeScript, C#)
- 🧩 Translating functional requirements into technical solutions that actually ship
- 🚀 Adapting fast — comfortable in both enterprise backends and modern SPA/cloud stacks
- 🇮🇩 UnPAM — Class leader 02TPLE002, GANJIL 2026/2027

---

### 🚀 Featured Projects

#### 📋 OpexAIO — Multi-Tenant SaaS Platform
All-in-one SaaS for operations teams — one Cloudflare Worker, one D1, one SPA.
`packages/*` Hono sub-routers mounted per product behind entitlement checks, all sharing users, tenants, and projects.

| Product | What it does |
|---|---|
| **PMO** | Task board, sprints, modules, TipTap wiki pages, calendar + gantt, saved views, customer portal + MCP tool server |
| **Timesheets** | Live timer, approval workflow with SHA-256 checksums, append-only audit, xlsx/CSV reports, Clockify push |
| **CRM** | Contacts, deals pipeline (kanban), companies, dashboard KPIs, task queue |
| **Expenses** | Bill capture → R2 → OCR → draft → two-tier approval → paid, project cost attribution |

**Stack:** Hono · Cloudflare Workers · D1 · Drizzle ORM · React · TypeScript · Tailwind · shadcn/ui

---

#### 🧾 OpexNOW / AMT e-Meterai — SAP → Peruri Digital Stamp
Enterprise B2B document automation: SAP delivery orders → stamped, signed, distributable electronic invoices.

- Syncs delivery orders + customer master data from SAP ERP
- Buyer confirmation via public PIN-protected link (mobile-friendly, GPS + photo evidence)
- SAP delivery confirmation (`zrest_doconfirm`) + invoice creation (`zr_createinv`)
- **Indonesian e-Meterai stamp** via Peruri (on-premise `signadapter` + KeyStamp signing)
- Email distribution + full audit log dashboard

**Stack:** Python · FastAPI · React · TypeScript · Tailwind · SAP RFC · Peruri SDK · MinIO S3

---

#### 🎓 RitmeKelas — Class Management & WhatsApp Notifications
University class manager — built as class lead. Attendance, schedule, tasks, and automated WhatsApp broadcasts.

- 📅 Teaching week engine (SKS-based, kelompok-aware, auto UTS/UAS skip)
- 📷 QR attendance with idempotent device-NIM binding
- 📊 Attendance matrix (roster × weeks, color-coded, print-to-PDF)
- 📲 WhatsApp weekly H-1 broadcasts via WAHA to multiple groups
- ⏰ In-app cron scheduler (Sunday 19:00 WIB), configurable from dashboard
- 📝 Tugas tambahan CRUD, roster management, single-admin auth

**Stack:** FastAPI · React 19 · TypeScript · Tailwind · SQLite · WAHA · Cloudflare tunnel

---

#### 📊 GetItDone — Personal Task Manager
TickTick-style single-user task manager. Capture tasks, organize into nested lists and tags, set priorities, recurring tasks (RRULE), full-text search.

- Inbox, Today, Next 7 Days, All Tasks, Completed smart views
- Nested lists with cycle-safe re-parenting, color-coded tags
- Dark/light themes, responsive mobile layout, paper-notebook UI

**Stack:** Hono · Cloudflare Workers · D1 · Drizzle ORM · React · TypeScript · TanStack Query · Tailwind · Turborepo

---

#### 📈 ForexArgent — Forex Research & Signal Tool
Trend-pullback strategy with honest backtests — real spread, commission, randomized slippage distribution.

- No strategy is trusted until it pays full execution costs
- Data pipeline + backtest engine (Phase 1), Telegram signal bot (Phase 2)

**Stack:** Python · MetaTrader5 · Telegram Bot API

---

### ⚒️ Tech Stack

<table>
<tr><td>

**Languages**
<br>
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=fff)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=fff)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat&logo=c-sharp&logoColor=fff)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=000)

</td><td>

**Frameworks**
<br>
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=fff)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=000)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat&logo=laravel&logoColor=fff)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django)

</td></tr>
<tr><td>

**Data**
<br>
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=fff)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=fff)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=fff)

</td><td>

**Platform**
<br>
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=fff)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=fff)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel)

</td></tr>
</table>

---

### 🏗️ Enterprise & OSS Contributions

| Repo | Description |
|---|---|
| [WFE_BPM](https://github.com/indraargamuria/WFE_BPM) | Wong Fong Engineering — BPM custom C# code for workflow automation |
| [L006_EpicorFieldService](https://github.com/indraargamuria/L006_EpicorFieldService) | Epicor Field Service customization |
| [L007_EpicorApproval](https://github.com/indraargamuria/L007_EpicorApproval) | Epicor approval workflow customization |
| [snbtbackend](https://github.com/indraargamuria/snbtbackend) | USS SNBT university application backend |
| [snbtfrontend](https://github.com/indraargamuria/snbtfrontend) | USS SNBT university application frontend |
| [dockerbackendpostgrestest](https://github.com/indraargamuria/dockerbackendpostgrestest) | .NET + PostgreSQL Docker test harness |

---

### 📚 Learning & Experiments

| Repo | Stack |
|---|---|
| [L001_TailwindMockup](https://github.com/indraargamuria/L001_TailwindMockup) | Tailwind CSS prototype |
| [L002_NextSupabaseWithAuth](https://github.com/indraargamuria/L002_NextSupabaseWithAuth) | Next.js + Supabase auth |
| [L003_TryoutGateway](https://github.com/indraargamuria/L003_TryoutGateway) | API gateway prototype |
| [L004_BirthdayLoveLetter](https://github.com/indraargamuria/L004_BirthdayLoveLetter) | Fun project |
| [L005_ExpoNativeWind](https://github.com/indraargamuria/L005_ExpoNativeWind) | React Native + NativeWind |
| [monorepo_tailwindreact_cloudflarehono](https://github.com/indraargamuria/monorepo_tailwindreact_cloudflarehono) | Turborepo template |
| [winrate-ibadah](https://github.com/indraargamuria/winrate-ibadah) | Prayer tracker |
| [project-uni-vault](https://github.com/indraargamuria/project-uni-vault) | University vault |

---

### 📫 Let's Connect

- 📱 WhatsApp: +62 821 1236 6956  
- 📸 [Instagram](https://instagram.com/indraargamuria)  
- 👔 [LinkedIn](https://linkedin.com/in/indraargamuria)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,100:00FFFF&height=100&section=footer"/>
</p>