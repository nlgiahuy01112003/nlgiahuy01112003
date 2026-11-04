# HỒ SƠ DỰ ÁN CHI TIẾT (PROJECT CONTEXT): `career` (Hồ Sơ Năng Lực Kỹ Sư Phần Mềm)

> **Dành cho AI Agents, LLM Chatbots & Kỹ sư Phần mềm:**  
> Tài liệu này cung cấp toàn bộ chi tiết về kho lưu trữ hồ sơ năng lực cá nhân và trang giới thiệu GitHub Profile của kỹ sư **Nguyễn Lê Gia Huy** (`nlgiahuy01112003`). Tài liệu bao quát các dự án trọng điểm, học vấn, kinh nghiệm làm việc thực tế, triết lý thiết kế hệ thống và bộ tiêu chuẩn kỹ năng.

---

## 1. Thông Tin Kỹ Sư & Định Vị Nghề Nghiệp

- **Họ và tên:** Nguyễn Lê Gia Huy (`nlgiahuy01112003`)
- **Học vấn:** Đại học Công nghệ TP.HCM (HUTECH) — Chuyên ngành Kỹ thuật Phần mềm (Tốt nghiệp Tháng 03/2026, GPA: 2.86 / 4.0)
- **Vị trí Ứng tuyển Mục tiêu:**
  1. *Full-Stack Software Engineer* (Next.js, React, NestJS, Express.js, TypeScript)
  2. *AI & RAG Systems Engineer* (Google Gemini 2.0/2.5 Flash, File Search Store, Pyodide WebAssembly, Kuromoji NLP, pgvector)
  3. *Backend & QA / Systems Engineer* (PostgreSQL, Prisma, Redis, Docker, GitHub Actions CI/CD)
- **Kinh Nghiệm Thực Tế:**
  - **DXCENTER (Trung tâm Chuyển đổi số TP.HCM):** Chuyên viên Hỗ trợ IT & Triển khai Hệ thống (Nhân viên Hợp đồng Dự án cấp Tỉnh, 08/2025 – 10/2025). Tuyển dụng cho dự án triển khai website dịch vụ công tại cấp xã/phường; đào tạo nghiệp vụ 2 cổng thông tin trong 2 tuần đầu và công tác thực địa 1.5 tháng tại Trung tâm Chuyển đổi số Phường Bình Khánh (hướng dẫn cán bộ/người dân, báo bug cho Dev L2, hỗ trợ thiết bị máy tính, mạng văn phòng và xác thực chữ ký số).
  - **EMPOWER SC:** IT Helpdesk / Manual Tester & System Deployment (12/2025 – 06/2026). Phát triển kiến trúc dịch vụ backend, tích hợp API thanh toán và quy trình làm việc tự động hóa AI.

---

## 2. Bản Đồ 6 Dự Án Trọng Điểm Trong Workspace

Mọi chatbot AI khi đọc hồ sơ phải đối chiếu chính xác với các dự án thực tế trong cùng workspace `E:\Project\projects`:

| Dự án | Thư mục | Kiến trúc Lõi | Điểm Nhấn Kỹ Thuật Đắt Giá |
| :--- | :--- | :--- | :--- |
| **TechStore (Vanfio)** | `tech-store/` | Next.js, NestJS, Prisma ORM, PostgreSQL, Redis, MoMo, Socket.IO | E-commerce đa kênh; quản lý tồn kho Serial/IMEI; Homepage Builder CMS động; Chat Gateway real-time; Kế toán kép tự động qua Transactional Outbox Worker. |
| **HyperGlot (v2.1)** | `HyperGlot/` | Turborepo, Next.js, NestJS, Flutter, Prisma, pgvector, Gemini 2.5 Flash | Học tiếng Nhật JLPT N5–N1; Lập lịch ôn tập ngắt quãng FSRS-4.5 (DSR model); AI Voicebot hội thoại thời gian thực; Phân tích cú pháp Kuromoji; Xuất Anki TSV. |
| **AI Mock Exam Platform** | `ai-exam-platform/` | Next.js App Router, NestJS, Pyodide WebAssembly, Neon PostgreSQL | Luyện thi kỹ sư AI theo chuẩn SFIA Level 3–4 (1.020 câu hỏi); chạy Python trực tiếp trên trình duyệt qua WebAssembly; Chấm điểm code AI tự động; Giáo trình AI/ML 4 chương. |
| **OptiBot RAG System (KB-Harvest)** | `kb-harvest/` | Python, Zendesk REST API, BeautifulSoup4, Gemini File Search, Docker | Pipeline thu thập tri thức tự động (36 bài viết); Delta Sync bằng mã băm SHA-256; Chunking 512/100 tokens lên Gemini File Search Store; Grounded RAG có trích dẫn nguồn. |
| **POMI Milk Tea** | `pomi/` | React, Express TypeScript, PostgreSQL, Socket.IO, Goong.io, Cloudinary | Đặt đồ uống chuỗi cửa hàng; Tính cự ly giao hàng thực tế qua Goong.io; Socket.IO phòng chi nhánh (`branch:${id}`) kèm bộ khử trùng lặp sự kiện trên client. |
| **Animated Portfolio** | `animated-portfolio/` | Vite 8, Express.js, Firebase Firestore, Typed.js, Lofi Music, ATS Scanner | Bàn làm việc Desktop Lofi tương tác; Bộ phân tích CV chuẩn ATS client-side; Bộ sinh CV may đo tự động; 25 bài tập code JS; Đa ngôn ngữ `vi`, `en`, `jp`. |

---

## 3. Các Quy Tắc Bất Biến Khi Cập Nhật Hồ Sơ

> [!CAUTION]
> 1. **Khớp 100% với Source Code:** Không quảng cáo các công nghệ không có trong mã nguồn thực tế (ví dụ: đã sửa `Python` thành `Python` cho `kb-harvest`, cập nhật đúng `ai-exam-platform` lên bản v2 Next.js + NestJS).
> 2. **Đường dẫn Uptime Ổn định:** Hình ảnh thống kê GitHub luôn sử dụng máy chủ `https://gh-stats.com/api?...` để tránh lỗi sập dịch vụ từ Vercel.
> 3. **Tính Duy Nhất Của Tệp:** Chỉ duy trì duy nhất tệp [`README.md`](file:///e:/Project/projects/career/README.md) làm profile chính, không để tệp rác bị trùng lặp.

