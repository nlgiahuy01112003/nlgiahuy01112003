# DETAILED PROJECT CONTEXT: `career` (Software Engineer Profile & CV Hub Repository)

> **For AI Agents, LLM Coding Assistants & Software Engineers:**  
> This document provides a complete breakdown of the GitHub Profile and Career repository for **Nguyen Le Gia Huy** (`nlgiahuy01112003`). It details the engineer's career positioning, flagship projects, academic credentials, work history, architectural principles, and the 9 specialized 2-page A4 CVs.

---

## 1. Professional Identity & Career Positioning

- **Full Name:** Nguyen Le Gia Huy (`nlgiahuy01112003`)
- **Education:** Ho Chi Minh City University of Technology (HUTECH) — Bachelor of Engineering in Information Technology, Software Engineering (`09/2021 – 03/2026`, GPA: `2.86 / 4.0`, `CEFR B1` English)
- **Target Engineering Roles:**
  1. *Full-Stack Software Engineer* (Next.js, React, NestJS, Express.js, TypeScript, Flutter)
  2. *AI & RAG Systems Engineer* (Google Gemini API, File Search RAG, Pyodide WebAssembly, TensorFlow.js WebGL, Kuromoji NLP, pgvector)
  3. *Backend / QA / IT Support & System Deployment Engineer* (PostgreSQL, Prisma ORM, Redis, Docker, GitHub Actions CI/CD, Manual E2E Testing, POS/ERP Deployment)
- **Professional Work Experience:**
  - **EMPOWER SC (`12/2025 – 06/2026`):** *IT Helpdesk / Manual Tester & System Deployment*. Supported production operations and executed end-to-end manual QA for the **Dimchan All-in-One POS/ERP** ecosystem across F&B and retail partner chains; validated POS terminal, K80 thermal receipt printer, and barcode scanner compatibility; troubleshot on-site network/hardware issues with a **> 95% First Contact Resolution (FCR)** rate.
  - **DXCENTER — HCMC Digital Transformation Center (`08/2025 – 10/2025`):** *IT Support & System Deployment Specialist (Project Contract)*. Recruited for web proficiency under a provincial digital transformation project deploying public web portals to grassroots wards/communes (contract concluded upon project completion). Completed **2 weeks (0.5 month)** of intensive workflow training on 2 municipal portals (`motcua.tphcm.gov.vn`, `qlvb.tphcm.gov.vn`), followed by **1.5 months** stationed on-site at **Binh Khanh Ward Digital Transformation Center** guiding civil servants and citizens, resolving user inquiries, reproducing bugs and escalating structured tickets to **Level 2 Developers (Dev L2)**, and maintaining PC hardware, office LAN networks, and digital signatures / authentication.

---

## 2. Cross-Project Reference Map (6 Flagship Projects)

| Project Name | Timeline | Core Tech Stack | Architectural Highlights |
| :--- | :--- | :--- | :--- |
| **HyperGlot** | `03/2026 – Present` | Turborepo, Next.js, NestJS, Flutter, Isar DB, Prisma ORM, Neon pgvector, TensorFlow.js | Enterprise Japanese learning monorepo (JLPT N5–N1); client-side TensorFlow.js WebGL stroke recognition & Kuromoji NLP ($0 API cost); offline-first Isar DB SRS mobile app; 60+ Playwright E2E tests. |
| **TechStore (Vanfio)** | `09/2025 – 03/2026` | Next.js, React, NestJS, Prisma ORM, PostgreSQL, Redis, MoMo, Socket.IO | High-concurrency e-commerce; PostgreSQL `SELECT FOR UPDATE` row-level locking (0% overselling); HMAC-SHA256 idempotent MoMo webhooks; `<50ms` `pg_trgm` trigram search; 95+ Lighthouse score. |
| **AI Mock Exam Platform** | `08/2026 – 09/2026` | Next.js App Router, NestJS, Pyodide WebAssembly, Gemini AI Grader, Neon PostgreSQL | SFIA Level 3–4 AI Engineer & Data Scientist assessment platform (1,020+ questions); in-browser Python/NumPy sandbox via Pyodide WebAssembly; Gemini AI Code Grader; MathJax LaTeX & Web Audio API; 24+ API tests. |
| **OptiBot RAG System (KB-Harvest)** | `06/2026 – 07/2026` | Python, Zendesk REST API, BeautifulSoup4, Gemini File Search, Docker, GitHub Actions | Automated knowledge harvesting & grounded RAG pipeline; multi-pass HTML-to-Markdown cleaner (40%+ token savings); SHA-256 delta sync (~85% fewer daily uploads); source URL citations. |
| **POMI Milk Tea** | `03/2024 – Present` | React, Express TypeScript, PostgreSQL, Socket.IO, Flutter, Gemini AI, Zalo Webhook, Goong.io | Real-time F&B ordering (`<800ms` Socket.IO push with UUID deduplication); Recipe & Ingredient Inventory Engine (separating Base drinks vs. Toppings with automated per-cup deduction); Gemini AI Inventory Assistant & automated Zalo low-stock alerts. |
| **Animated Portfolio** | `2025 – Present` | Vite, Vanilla ES Modules, Express.js, Firebase Firestore, PDF.js, Mammoth.js | Interactive Lofi desktop workspace; client-side ATS Resume Scanner & Auto-Tailor CV Engine; 25 JS coding challenges; JWT-protected CV-Vault; trilingual localization (`vi`, `en`, `jp`). |

---

## 3. Repository Structure (`nlgiahuy01112003/nlgiahuy01112003`)

- [`README.md`](file:///e:/Project/projects/career/README.md): Main GitHub Profile README featuring custom animated SVG banners, engineering KPI cards, Mermaid system architecture diagram, specialized CV Hub table, and expandable production bug case studies.
- [`assets/`](file:///e:/Project/projects/career/assets): Self-hosted custom SVGs ([`hero-banner.svg`](file:///e:/Project/projects/career/assets/hero-banner.svg) and [`engineering-metrics.svg`](file:///e:/Project/projects/career/assets/engineering-metrics.svg)) ensuring zero third-party downtime.
- [`cv/`](file:///e:/Project/projects/career/cv): All **9 specialized HTML & PDF resumes** (Full-Stack VI/EN, Frontend VI/EN, Backend VI/EN, IT Helpdesk/Tester VI/EN, Product Support EN), strictly formatted to **2 A4 pages** with technology version numbers omitted.
