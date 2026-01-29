# 🚀 AquilaSense ML Ops

**Production-Grade Distributed ML Decision & Observability Platform**

A full-stack, production-style ML Ops & Decision Intelligence system inspired by real-world internal tools.

---

## ✨ Key Features

- 📊 **Operational Dashboard**
  - Total requests, P95 latency, accuracy %, error rate
  - Latency distribution + trends
- 🧠 **ML Decision Engine**
  - Mock inference scoring + confidence
- 🏆 **Ranking System**
  - Weighted scoring with latency penalty
- 🔍 **Explainability View**
  - Transparent decision logic breakdown
- 🧪 **Analytics APIs**
  - Health checks, metrics aggregation, decisions feed

---

## 🧮 Ranking Formula (inline, no extra code box)

weighted_score = score * 0.7 + confidence * 30 - latency_ms * 0.01

---

## 🛠️ Tech Stack

- Frontend: Next.js (App Router), TypeScript, Tailwind CSS
- Backend: Next.js API Routes
- Charts: Recharts
- Design: Internal-tool inspired dark UI
