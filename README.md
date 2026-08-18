# Enterprise Tech Stack Architecture

## Stack Overview

### Frontend
* **Framework:** Next.js
* **Styling:** Tailwind CSS
* **Language:** TypeScript

### Mobile
* **Framework:** Flutter

### Backend
* **Runtime:** Node.js
* **Framework:** NestJS 11
* **Database:** PostgreSQL (AWS RDS)
* **ORM:** Prisma 7
* **Authentication:** JWT + Passport.js
* **File & Media Storage:** Cloudflare R2 / Stream (Images, Documents, Video with HLS streaming)
* **Email Service:** Nodemailer (SMTP)
* **API Documentation:** Swagger / OpenAPI
* **Cache & In-Memory Store:** Redis

### Cloud & Infrastructure
* **Provider:** Amazon Web Services (AWS)

---

## Why This Stack Was Chosen

* **Performance & Scalability:** Next.js, Flutter, and NestJS deliver a battle-tested foundation for high-throughput enterprise workloads, fast cross-platform delivery, and flexible API architecture.
* **End-to-End Type Safety:** Unifying the codebase around TypeScript, Prisma 7, and OpenAPI eliminates interface mismatches, catches errors at compile-time, and accelerates team velocity.
* **Optimized Infrastructure Costs:** Pairing managed AWS PostgreSQL with Cloudflare for global media asset and HLS video delivery significantly cuts data egress fees while maintaining enterprise-grade reliability.
