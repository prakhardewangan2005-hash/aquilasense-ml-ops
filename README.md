# 🚀 AquilaSense ML Ops

**Production-Grade Distributed ML Decision & Observability Platform**

A full-stack, production-style ML Ops system inspired by real-world internal tools used at large tech companies.  
This project demonstrates **ML system design, observability, ranking logic, API design, and dashboarding**.

---

## ✨ Key Highlights

- 📊 Internal-tool style dashboard (metrics, latency, accuracy)
- 🧠 Decision ranking engine with weighted scoring
- 🩺 Health & observability APIs
- 📈 Analytics & monitoring views
- 🧩 Modular, production-oriented architecture

---

## 🧠 Decision Ranking Logic

weighted_score = score * 0.7 + confidence * 30 - latency_ms * 0.01

Used to sort and surface top ML decisions in the Rank view.

---

## 🛠️ Tech Stack

- **Frontend:** Next.js (App Router), TypeScript, Tailwind CSS  
- **Backend:** Next.js API Routes  
- **Charts:** Recharts  
- **Design:** Internal-tool inspired UI  
- **Architecture:** Modular & production-oriented

---

## 📂 Project Structure

src/
├── app/
│ ├── dashboard/page.tsx
│ ├── ingest/page.tsx
│ ├── rank/page.tsx
│ ├── explain/page.tsx
│ ├── analytics/page.tsx
│ └── api/
│ ├── health/route.ts
│ ├── metrics/route.ts
│ ├── decisions/route.ts
│ └── analytics/route.ts
│
├── lib/
│ ├── ranking.ts
│ ├── metrics.ts
│ └── mockData.ts


---

## ▶️ Running Locally

``bash
npm install
npm run dev

🌐 Access (Local)

App Dashboard: http://localhost:3000/dashboard

Health API: http://localhost:3000/api/health

⚠️ Note: Localhost works only while the dev server is running.

---

🏗️ Architecture Overview

Browser (UI)
   ↓
Next.js App Router (Pages)
   ↓
API Routes (/api/*)
   ↓
Core Logic (lib/)
   ├─ ranking.ts
   ├─ metrics.ts
   └─ mockData.ts

---

🎯 Purpose

This project is built to demonstrate:

ML Ops system thinking

Observability & monitoring design

Ranking & decision intelligence

Clean, production-style code structure

It is intended for internship / new-grad evaluation, not as a consumer product.

