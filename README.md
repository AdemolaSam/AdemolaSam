# Ademola Oduntan
## Full-Stack Engineer
📧 oduntanade2721@gmail.com | 📱 +234 8134667940
📍 Nigeria
[LinkedIn](https://www.linkedin.com/in/ademola-oduntan-8a5b6b284) | [GitHub](https://github.com/AdemolaSam)

## Summary
Full-Stack Engineer specializing in Distributed Systems and Blockchain. Proven track record in architecting multi-tenant SaaS, high-concurrency automation pipelines, and secure on-chain protocols

## Technical Skills
- **Backend:** Node.js, NestJS, Express.js, FastAPI (Python)
- **Frontend:** React.js, Next.js
- **Languages:** TypeScript, JavaScript, Python, Rust
- **Databases:** PostgreSQL, MySQL, MongoDB, Redis
- **Async & Queues:** BullMQ, Celery, Redis (broker, caching, rate limiting)
- **Automation:** Playwright, HTTPX
- **Cloud & Storage:** Cloudflare R2, AWS S3
- **DevOps:** Docker, Docker Compose, CI/CD (GitHub Actions)
- **API & Docs:** REST, JWT, OAuth, OpenAPI/Swagger, TSOA
- **Blockchain:** Solana, Anchor Framework, Rust
- **Tools:** Git, Postman, Prisma ORM, Sequelize ORM

## Professional Experience

### Full-Stack Developer | Krikia (Real Estate Platform)
*May 2024 – October 2025*
- Built backend APIs for property bookings, payments, and transaction workflows using NestJS
- Integrated Flutterwave and Monnify payment gateways with wallet system, invoice
  generation, and automated billing logic
- Developed agent onboarding pipeline, referral tracking system, and commission
  calculation logic with role-based access control
- Built property inspection booking system with calendar scheduling and notification workflows
- Developed multiple Next.js dashboards for property management, agent operations,
  and financial reporting (Next.js/NestJS monorepo)

### Co-Founder & Lead Backend Engineer | Farman.ng
*January 2024 – Present*
- Architected multi-tenant SaaS e-commerce platform with vendor isolation and
  role-based access control using Express.js, TSOA, and MySQL
- Implemented multi-vendor wallet system funded via Monnify and Paystack reserved accounts,
  with fund routing, balance tracking, and transaction audit trail
- Integrated BullMQ for background job processing — email/OTP delivery and automatic
  wallet creation on user signup
- Migrated codebase from JavaScript to TypeScript, enforcing strict type safety
- Built secure file upload pipeline with Cloudflare R2 and AWS S3 using pre-signed URLs
- Set up CI/CD pipeline with GitHub Actions; services containerised with Docker

### Backend Engineer | Job Automation Platform (Confidential)
*2025 – Present*
- Architected distributed job automation platform serving multiple users, each processing
  30–50 job applications per day
- Built FastAPI backend with auth, bot control, CV ingestion, job tracking, and admin endpoints
- Designed Celery pipeline with three worker processes: job scraping (HTTPX + Playwright
  across multiple ATS), PostgreSQL full-text search matching, and automated form submission
- Integrated LLM to generate contextual answers to open-ended application questions at runtime
- Implemented Playwright automation with stealth mode and human fingerprinting
- Applied Redis for message brokering, caching, and per-endpoint rate limiting
- Containerised all services with Docker Compose; CI/CD and deployment in progress

## Projects

### [Memo — Solana Transaction Journal](https://github.com/AdemolaSam/memo)
*Solana Mobile Monolith Hackathon, 2026*
- Built full-stack mobile app (React Native + Expo) with Express/TypeScript backend,
  Prisma ORM, and Supabase (PostgreSQL)
- Client-side NaCl encryption — plaintext notes never reach the backend; keypair derived
  deterministically from wallet signature
- Helius webhook integration for real-time transaction parsing; Firebase Cloud Messaging
  (FCM) for push notifications on transaction landing
- On-chain notarization: SHA-256 hash written to Solana Memo Program for tamper-proof,
  timestamped proof without exposing note content
- Wallet-based auditor sharing with individually re-encrypted copies, revocable at any time

### [SubStream — Decentralised Subscription Platform](https://substream-app.vercel.app)
- On-chain subscription and payment logic built in Rust using the Anchor framework
- PDA-based access control with on-chain payment verification
- 100% test coverage on all program instructions

### [Task-Me-AI — AI Task Management](https://task-me-ai.vercel.app)
- NestJS backend with OpenAI integration for task decomposition and priority ranking
- PostgreSQL schema with JWT authentication and role-based access control

## Education
**Bachelor of Education (Honours), Upper Second Class**
University of Calabar | 2022

## Certifications
- KCNA, Linux Foundation — In Progress (2026)
- Kaggle 5-Day Generative AI Intensive (Google Developers) (2025)
- Turbin3 Builders Cohort, Q1 — Solana (2026)
- Ackee School of Solana Program (2025)
- Backend Engineering — DevCareer Africa (2024)
- Microsoft AI Career Essentials (2025)
- Google Data Analytics — Coursera (2023)
