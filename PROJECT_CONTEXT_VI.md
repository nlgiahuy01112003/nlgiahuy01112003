# HỒ SƠ DỰ ÁN CHI TIẾT (PROJECT CONTEXT): `career` (Hồ Sơ Năng Lực Kỹ Sư Phần Mềm)

> **Dành cho AI Agents, LLM Chatbots & Kỹ sư Phần mềm:**  
> Tài liệu này cung cấp toàn bộ chi tiết về kho lưu trữ hồ sơ năng lực cá nhân và trang giới thiệu GitHub Profile của kỹ sư **Nguyễn Lê Gia Huy** (`nlgiahuy01112003`). Tài liệu bao quát các dự án trọng điểm, học vấn, kinh nghiệm làm việc thực tế, triết lý thiết kế hệ thống và bộ CV chuyên biệt.

---

## 1. Thông Tin Kỹ Sư & Định Vị Nghề Nghiệp

- **Họ và tên:** Nguyễn Lê Gia Huy (`nlgiahuy01112003`)
- **Học vấn:** Đại học Công nghệ TP.HCM (HUTECH) — Kỹ sư Công nghệ thông tin, Chuyên ngành Công nghệ Phần mềm (`09/2021 – 03/2026`, GPA: `2.86 / 4.0`, Tiếng Anh `CEFR B1`)
- **Vị trí Ứng tuyển Mục tiêu:**
  1. *Full-Stack Software Engineer* (Next.js, React, NestJS, Express.js, TypeScript, Flutter)
  2. *AI & RAG Systems Engineer* (Google Gemini API, File Search RAG, Pyodide WebAssembly, TensorFlow.js WebGL, Kuromoji NLP, pgvector)
  3. *Backend / QA / IT Support & Systems Deployment Engineer* (PostgreSQL, Prisma ORM, Redis, Docker, GitHub Actions CI/CD, Manual E2E Testing, POS/ERP Deployment)
- **Kinh Nghiệm Làm Việc Thực Tế:**
  - **EMPOWER SC (`12/2025 – 06/2026`):** *IT Helpdesk / Kiểm thử thủ công & Triển khai hệ thống*. Vận hành, hỗ trợ kỹ thuật và kiểm thử E2E hệ sinh thái quản trị bán hàng **Dimchan All-in-One POS/ERP** cho chuỗi đối tác F&B và bán lẻ; kiểm tra tương thích thiết bị POS, máy in nhiệt K80, mạng LAN/Wi-Fi tại cửa hàng với tỷ lệ giải quyết sự cố tại chỗ (**FCR > 95%**).
  - **DXCENTER — Trung tâm Chuyển đổi số TP.HCM (`08/2025 – 10/2025`):** *Chuyên viên Hỗ trợ IT & Triển khai Hệ thống (Hợp đồng Dự án)*. Tuyển dụng theo dự án cấp tỉnh triển khai website dịch vụ công cho các đơn vị xã/phường dành cho nhân sự am hiểu về Web (kết thúc hợp đồng khi hoàn thành dự án). **0.5 tháng đầu (2 tuần)** đào tạo chuyên sâu luồng nghiệp vụ 2 cổng thông tin (`motcua.tphcm.gov.vn`, `qlvb.tphcm.gov.vn`); **1.5 tháng sau** công tác trực tiếp tại **Trung tâm Chuyển đổi số Phường Bình Khánh** hướng dẫn cán bộ và người dân sử dụng 2 website, giải đáp thắc mắc, tiếp nhận phản hồi, tái hiện và gửi yêu cầu sửa bug cho **Dev L2**, đồng thời hỗ trợ thiết bị phần cứng, mạng LAN và chữ ký số / xác thực số.

---

## 2. Bản Đồ 6 Dự Án Trọng Điểm Trong Workspace

Mọi chatbot AI khi đọc hồ sơ phải đối chiếu chính xác với các dự án thực tế trong cùng workspace `E:\Project\projects`:

| Dự án | Thời gian | Kiến trúc Lõi | Điểm Nhấn Kỹ Thuật Đắt Giá |
| :--- | :--- | :--- | :--- |
| **HyperGlot** | `03/2026 – Hiện tại` | Turborepo, Next.js, NestJS, Flutter, Isar DB, Prisma ORM, Neon pgvector, TensorFlow.js | Hệ sinh thái học tiếng Nhật JLPT N5–N1; Edge AI nhận diện nét chữ Kanji bằng TensorFlow.js WebGL & tách từ Kuromoji ($0 phí API); học thẻ nhớ SRS offline với Isar DB; 60+ Playwright E2E tests. |
| **TechStore (Vanfio)** | `09/2025 – 03/2026` | Next.js, React, NestJS, Prisma ORM, PostgreSQL, Redis, MoMo, Socket.IO | E-commerce kiểm soát tương tranh cao; khóa dòng PostgreSQL `SELECT FOR UPDATE` chống overselling 100%; MoMo Webhook lũy đẳng HMAC-SHA256; tìm kiếm `pg_trgm` < 50ms; Lighthouse 95+. |
| **AI Mock Exam Platform** | `08/2026 – 09/2026` | Next.js App Router, NestJS, Pyodide WebAssembly, Gemini AI Grader, Neon PostgreSQL | Nền tảng thi thử & chấm code Kỹ sư AI theo chuẩn SFIA Level 3–4 (1.020+ câu hỏi); chạy sandbox Python trực tiếp trên trình duyệt qua Pyodide WebAssembly; MathJax LaTeX & Web Audio API; 24+ API tests. |
| **OptiBot RAG System (KB-Harvest)** | `06/2026 – 07/2026` | Python, Zendesk REST API, BeautifulSoup4, Gemini File Search, Docker, GitHub Actions | Pipeline ETL & RAG tự động; làm sạch HTML sang Markdown tiết kiệm 40%+ token; SHA-256 Delta Sync giảm ~85% lượng upload hàng ngày; Grounded RAG kèm trích dẫn URL nguồn. |
| **POMI Milk Tea** | `03/2024 – Hiện tại` | React, Express TypeScript, PostgreSQL, Socket.IO, Flutter, Gemini AI, Zalo Webhook, Goong.io | Đặt món F&B đồng bộ real-time < 800ms kèm bộ lọc khử trùng lặp đơn hàng ma; Quản lý Công thức & Tồn kho Nguyên liệu (tách biệt Base Ingredient pha chế & Topping, tự động trừ kho theo ly); Trợ lý AI Gemini & cảnh báo Zalo tự động khi nguyên liệu sắp hết. |
| **Animated Portfolio** | `2025 – Hiện tại` | Vite, Vanilla ES Modules, Express.js, Firebase Firestore, PDF.js, Mammoth.js | Bàn làm việc Desktop Lofi tương tác; ATS Resume Scanner & Auto-Tailor CV Engine chạy client-side; 25 bài tập code JS Learning Hub; CV-Vault bảo mật JWT; Đa ngôn ngữ `vi`, `en`, `jp`. |

---

## 3. Cấu Trúc Thư Mục Repository `career` (`nlgiahuy01112003/nlgiahuy01112003`)

- [`README.md`](file:///e:/Project/projects/career/README.md): Trang GitHub Profile chính thức, tích hợp SVG banner động, bảng KPI kỹ thuật, sơ đồ kiến trúc Mermaid, bảng tải 9 CV chuyên biệt và 3 Case Studies thực chiến.
- [`assets/`](file:///e:/Project/projects/career/assets): Chứa [`hero-banner.svg`](file:///e:/Project/projects/career/assets/hero-banner.svg) và [`engineering-metrics.svg`](file:///e:/Project/projects/career/assets/engineering-metrics.svg) tự chủ 100% (không phụ thuộc server bên thứ ba).
- [`cv/`](file:///e:/Project/projects/career/cv): Chứa trọn bộ **9 file CV HTML và 9 file CV PDF** (5 vị trí: Full-Stack VI/EN, Frontend VI/EN, Backend VI/EN, IT Helpdesk/Tester VI/EN, Product Support EN) đã chuẩn hóa định dạng in đúng **2 trang A4** và không ghi số phiên bản công nghệ.
