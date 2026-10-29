<div align="center">

<!-- Status Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20OPPORTUNITIES-34C759?style=for-the-badge&logo=statuspage&logoColor=white&labelColor=0D1117" alt="Status" />
  <img src="https://img.shields.io/badge/LOCATION-CAN%20THO%2C%20VIETNAM-0071E3?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0D1117" alt="Location" />
</p>

# Nguyen Dinh Hau

### Fullstack Software Engineer · TypeScript / Next.js / Node.js

<p align="center">
  <i>"Focused on writing clean, well-structured code with strong foundations in TypeScript, Next.js, and modern relational databases."</i>
</p>

<!-- Quick Action Badges -->
<p align="center">
  <a href="mailto:hau.nguyen.personal@gmail.com">
    <img src="https://img.shields.io/badge/Email-hau.nguyen.personal%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/hau0909">
    <img src="https://img.shields.io/badge/GitHub-hau0909-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/h%E1%BA%ADu-nguy%E1%BB%85n-26ab12381/">
    <img src="https://img.shields.io/badge/LinkedIn-Nguyen%20Dinh%20Hau-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

</div>

## Engineering Overview

<div align="center">

|                         Code Organization                          |                        Fullstack Ecosystem                         |                      Data & Permissions                       |                            Integrations                            |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :-----------------------------------------------------------: | :----------------------------------------------------------------: |
| **Layered Conventions**<br><sub>Clear Separation of Concerns</sub> | **Next.js & Supabase**<br><sub>App Router · PostgreSQL · RLS</sub> | **Multi-Role RBAC**<br><sub>Normalized Database Schemas</sub> | **Real-Time & Payments**<br><sub>SePay Webhook · Matrix E2EE</sub> |

</div>

> **Software Engineering student at FPT University** (Graduating 10/2026) with fullstack development experience across enterprise internship (TekNix) and capstone course projects. Passionate about clean code practices, type-safe architectures, and building dependable web applications.

---

## Engineering Highlights

### 01. SGCMP — Security Guard Connection & Management Platform

_Enterprise Hybrid Security Marketplace & Multi-Tenant SaaS Suite_  
**Role:** Capstone Team Leader & Software Architect / Fullstack Developer _(Team of 5)_

- **Architectural Leadership:** Formulated and standardized 4-layer architectural conventions (Controller → Service → Repository → Model) across a 5-developer team, eliminating cross-layer coupling.
- **Multi-Tenant Isolation & RBAC:** Engineered normalized PostgreSQL schemas supporting strict data isolation and permission barriers across **6 distinct user roles**.
- **End-to-End B2B Lifecycle:** Architected the complete B2B service pipeline: demand survey, guard assignment verification, quotation approval, and bilateral digital contract signing.
- **Financial Integrity:** Integrated dynamic VietQR payment automation coupled with an idempotent SePay webhook receiver, guaranteeing atomic subscription provisioning and tamper-proof payment reconciliation.
- **Tech Stack:** `Next.js` · `TypeScript` · `Node.js` · `Express.js` · `PostgreSQL` · `SePay VietQR` · `Tailwind CSS` · `Shadcn UI`

---

### 02. Homestay Booking Ecosystem — Storefront & Operations Console

_Comprehensive Travel Booking & Tour Experience Platform_  
**Role:** Capstone Team Leader & Software Architect / Fullstack Developer _(Team of 5)_

- **Dual-Portal System:** Architected and delivered two interoperable applications:
  - **Storefront:** 40 Next.js App Router pages, 117 service modules, and 18 enforced business rules managing inventory, real-time pricing, and booking state machines (`DRAFT` → `PENDING` → `CONFIRMED` → `COMPLETED`).
  - **Admin Operations Console:** 8-page command dashboard monitoring 11 operational metrics, multi-stage host onboarding verification (`pending` → `approved` / `resubmit`), and listing moderation.
- **Defensive Concurrency & Inventory:** Designed calendar-backed date-blocking and per-slot capacity checks on Supabase PostgreSQL with Row Level Security (RLS) and guarded PostgREST updates.
- **Scale:** 35,700+ combined LOC · 33 normalized relational tables · 5 Supabase Storage buckets · 260+ structured Git commits.
- **Tech Stack:** `Next.js 16 (App Router)` · `React 19` · `TypeScript 5` · `Supabase (PostgreSQL, Auth, RLS, Storage)` · `Tailwind CSS 4` · `Recharts`

---

### 03. Decentralized Matrix Web Messenger

_Enterprise Secure Messaging Client powered by Matrix Open Standard_  
**Role:** Fullstack Developer Intern — TekNix Technology JSC _(05/2025 – 08/2025)_

- **End-to-End Encryption (E2EE):** Configured real-time cryptographic synchronization pipelines via the Matrix JS SDK, ensuring confidential client-to-server and room-level communication.
- **High-Volume Virtualization:** Implemented virtualized message stream rendering integrated with Zustand state management, eliminating layout thrashing and maintaining smooth 60fps scrolling in high-concurrency chat rooms.
- **Core Collaboration:** Shipped live text streaming, thread replies, message forwarding, and optimistic UI updates under high network latency.
- **Tech Stack:** `Matrix Protocol SDK` · `TypeScript` · `React.js` · `Zustand` · `Virtualized List` · `Tailwind CSS`

---

### 04. Matchome — Intelligent Accommodation & Roommate Engine

_Campus-Centric Roommate Finding Platform tailored for University Students_  
**Role:** Solo Fullstack Developer

- **Constraint-Aware Compatibility:** Designed an automated evaluation engine utilizing LLM structured JSON Schema outputs to enforce absolute living constraints (curfews, smoking, pets) and compute weighted lifestyle compatibility scores.
- **Fullstack Ownership:** Independently developed the end-to-end application with Next.js and Supabase, implementing geospatial campus filters and fluid micro-interactions with Framer Motion.
- **Tech Stack:** `Next.js 15` · `TypeScript` · `Supabase` · `Tailwind CSS` · `Framer Motion` · `Structured Output AI Engine`

---

## Technical Skills

<div align="center">

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

| Layer                        | Technologies & Standards                                                                                                                                   |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **System & Architecture**    | Layered Architecture · Multi-Tenant Isolation · Role-Based Access Control (RBAC) · Booking State Machines · Webhook Idempotency · Client-BaaS Architecture |
| **Languages**                | TypeScript · JavaScript · SQL · HTML5 / CSS3                                                                     |
| **Frontend/Mobile Engineering**     | Next.js · React 19 · Tailwind CSS v4 · Shadcn UI · Radix UI · Zustand · React Native                                    |
| **Backend & Persistence**    | Node.js · Express.js · PostgreSQL · Supabase _(RLS Policies, Auth, Realtime, Storage)_ · RESTful API Design                                                |
| **Integrations & Protocols** | VietQR / SePay Webhook · Matrix Protocol _(E2EE)_ · Nodemailer                                                                                             |
| **Quality & Operations**     | Git / GitHub Flow · Conventional Commits · Postman · Defensive Code Contracts · Automated Markdown Verification                                            |

</div>

---

## Engineering Principles

- **Clean Separation of Concerns**  
  Every module has a single responsibility. Business logic is kept separate from UI presentation, and database calls follow clear data access patterns.

- **Data Integrity over Convenience**  
  Transactions, state transitions, and status updates are guarded at the persistence layer. We never assume client state is authoritative, especially for financial transactions and booking availability.

- **Code as Documentation**  
  Predictable directory structures, explicit TypeScript interfaces, and Conventional Commits make projects easy to navigate and maintain for any developer joining the codebase.

---

## Certifications & Foundations

- [Software Development Lifecycle (SDLC)](https://coursera.org/share/8d115d63d7ac6c2c38a00a463261f8aa)
- [Project Management Principles & Practices](https://coursera.org/share/d5f87364d956acb41ebad45d7397b1c8)
- [User Experience (UX) Research and Design](https://coursera.org/share/fa94e3dbd48138368500bf054b281058)
- [CertNexus Certified Ethical Emerging Technologist](https://coursera.org/share/93cb93204bad6700265c46f46e3d20a4)
- [Web Design for Everybody: Basics & Modern Standards](https://coursera.org/share/08cc417d57b3c369fd296b50f9fd3249)

---

</div>
