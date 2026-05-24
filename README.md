# 👋 Hi, I'm Gia Huy — Software Engineer

<div align="center">

### 🚀 Building high-performance, concurrent Web & Mobile applications with production-grade architectures

[![GitHub](https://img.shields.io/badge/GitHub-nlgiahuy01112003-181717?style=for-the-badge&logo=github)](https://github.com/nlgiahuy01112003)
[![Email](https://img.shields.io/badge/Email-Job.nlgiahuy@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Job.nlgiahuy@gmail.com)
[![Facebook](https://img.shields.io/badge/Facebook-CIRTDARK-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/CIRTDARK)

</div>

---

## 🧑‍💻 About Me

- 🎓 **Software Engineering** graduate from **HUTECH University** (March 2026).
- 💼 Former **IT Support & Helpdesk Intern** at **HCMC Digital Transformation Center (DXCENTER)**.
- ⛩️ Creator of **HyperGlot** — an enterprise-grade Japanese learning monorepo (Turborepo) with edge AI and offline-first mobile sync.
- 🛒 Creator of **TechStore** — a production-grade e-commerce engine with 40+ endpoints and strict concurrency control.
- 🤝 Experienced in **Agile/Scrum** environments, unit testing, E2E testing, and designing secure, role-based workflows (RBAC).
- 🌱 Deeply passionate about **System Architecture**, **Performance Optimization**, and **DevOps**.

---

## 💻 Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-444?style=flat-square) ![TanStack Table](https://img.shields.io/badge/TanStack_Table-FF4154?style=flat-square&logo=react&logoColor=white) ![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat-square) |
| **Mobile** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Riverpod](https://img.shields.io/badge/Riverpod-02569B?style=flat-square) |
| **Backend & Caching** | ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![BullMQ](https://img.shields.io/badge/BullMQ-orange?style=flat-square) |
| **Databases & Search** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Meilisearch](https://img.shields.io/badge/Meilisearch-00adb5?style=flat-square) ![Isar DB](https://img.shields.io/badge/Isar_DB-02569B?style=flat-square) |
| **Testing & CI/CD** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![React Testing Library](https://img.shields.io/badge/React_Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **DevOps & Tools** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) |

---

## 🧠 Engineering Judgment

I believe that engineering is about making deliberate trade-offs to build reliable systems:
- **Type Safety End-to-End**: I prioritize **TypeScript (Next.js + NestJS)** across the stack. Sharing type definitions from the database schema (via Prisma) all the way to the frontend ensures API contracts never break silently.
- **Edge Computing & Zero-Cost NLP**: In HyperGlot, I chose to process kanji stroke recognition locally on the user's browser using **TensorFlow.js & WebGL** and tokenization via **kuromoji.js**, removing server payload bottlenecks and completely eliminating API costs.
- **Data Integrity & Locking**: For checkout flows, I avoid document databases like MongoDB and use **PostgreSQL with database transactions and row-level locking (`SELECT FOR UPDATE`)** to prevent race conditions (like overselling the last item in stock) under high concurrent traffic.
- **Offline-First Mobile Architecture**: For mobile learning, I utilize **Flutter** with **Isar DB** to ensure SRS cards are instantly reviewable offline. Syncs are performed asynchronously via WebSockets/REST once connectivity is restored.

---

## 🏆 Featured Projects

### ⛩️ [HyperGlot — AI-Driven Japanese Language Ecosystem](https://github.com/nlgiahuy01112003/HyperGlot) (Monorepo)
> Enterprise-grade language learning platform designed under a strict Zero-Cost API Strategy.

- 🏗️ **Turborepo Monorepo**: Integrates `apps/web` (Next.js 14), `apps/admin` (Next.js dashboard with TanStack Table & Recharts), `apps/mobile` (Flutter app with Riverpod & Isar local DB), and `apps/api` (NestJS backend).
- ⚡ **Edge Computing First**: Localized kanji stroke recognition using TensorFlow.js & WebGL. Morphological tokenization processed client-side via kuromoji.js.
- 🔍 **Semantic Search**: Bypasses expensive managed vector databases by utilizing PostgreSQL's native `pgvector` extension for semantic JLPT question retrieval.
- 🧪 **Testing & QA**: Over 60+ automated test cases, including Playwright E2E testing for auth/lessons/dashboard, multi-browser configurations, WCAG 2.1 AA accessibility compliance, and OWASP Top 10 security audits.
- 🐳 **Infrastructure**: Docker Compose production stack (Next.js, NestJS, Postgres, Redis, Nginx reverse proxy). Centralized caching & BullMQ queues.

---

### 🛒 [TechStore — E-commerce Electronics Platform](https://github.com/nlgiahuy01112003/techstore)
> Production-grade electronics e-commerce platform featuring administrative dashboards, scalable APIs, and payment integrations.

- 🔒 **Concurrency Control**: Implemented PostgreSQL `SELECT FOR UPDATE` row-level locks inside database transaction blocks, ensuring zero inventory overselling when multiple users checkout the final items simultaneously.
- 💳 **Secure Payment Integration**: Implemented a secure sandbox payment checkout with MoMo and VNPay wallets, backed by server-side webhook verification.
- 🔍 **Optimized Search**: Integrated Meilisearch to achieve sub-50ms typo-tolerant product searches.
- 💬 **Real-time Helpdesk**: Bidirectional client-admin chat routing using Socket.IO.
- 🛡️ **Clean Architecture**: 40+ endpoints written in NestJS (with strict standard DTOs and complete avoidance of `any` types), guarded by JWT authentication + Google OAuth 2.0 with Role-Based Access Control (RBAC).

---

### 🧋 [POMI Milk Tea — Real-Time F&B Ordering System](https://github.com/nlgiahuy01112003/pomi_web)
> Full-stack F&B management system with 3 distinct dashboards (React) and a Flutter mobile application.

- 📊 **Real-time Order Syncing**: Used Socket.IO to instantly synchronize order state between customers, cashiers, and kitchen devices with under 1-second latency.
- 🛠️ **Reconnection Deduplication**: Formulated a client-side deduplication mechanism tracking order IDs and "last seen" timestamps to solve duplicate order replay issues when WebSockets reconnected.
- 📍 **Geolocation Routing**: Integrated Goong.io APIs to power the store locator, calculate branch geolocations, and estimate delivery distances.
- 🤖 **AI Customer Service**: Integrated Google Gemini AI to assist customers with dynamic menu queries and order routing.

---

## 💼 Work Experience

### 💻 Former IT Support / Helpdesk Intern
**HCMC Digital Transformation Center (DXCENTER)** | *Aug 2025 – Oct 2025*
- Handled technical troubleshooting, bug identification, and hardware maintenance for high-traffic public administration software ecosystems (`motcua.tphcm.gov.vn`, `qlvb.tphcm.gov.vn`).
- Analyzed large data transactions, gaining firsthand experience in managing public sector infrastructure supporting thousands of daily concurrent users.

---

## 🎓 Academic Projects

### 📈 Credit Repayment Risk Prediction
**Python / Support Vector Machines (SVM) / Tkinter**
- Designed a machine learning desktop application to classify credit risk based on user profiles.
- Solved a severe data imbalance (90/10 split) using **SMOTE** (Synthetic Minority Over-sampling Technique) and optimized the SVM model using Grid Search for hyperparameter tuning.

---

## 📊 GitHub Stats

<div align="center">

[![Gia Huy's GitHub Stats](https://github-readme-stats.vercel.app/api?username=nlgiahuy01112003&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/anuraghazra/github-readme-stats)
[![Gia Huy's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nlgiahuy01112003&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)

</div>

