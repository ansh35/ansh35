<div align="center">
  <img src="[https://capsule-render.vercel.app/api?type=waving&color=0:09090b,50:0284c7,100:09090b&height=220&section=header&text=Ansh%20Khare&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Engineer%20%7C%20Distributed%20Web%20Architectures%20%26%20Agentic%20AI&descAlignY=58&descSize=18](https://capsule-render.vercel.app/api?type=waving&color=0:09090b,50:0284c7,100:09090b&height=220&section=header&text=Ansh%20Khare&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Engineer%20%7C%20Distributed%20Web%20Architectures%20%26%20Agentic%20AI&descAlignY=58&descSize=18)" width="100%" />

  <p align="center">
    <a href="[https://anshkhare-portfolio.vercel.app/](https://anshkhare-portfolio.vercel.app/)"><img src="[https://img.shields.io/badge/Live_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white](https://img.shields.io/badge/Live_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)" /></a>
    <a href="[https://www.linkedin.com/in/ansh-khare-4019a53aa](https://www.linkedin.com/in/ansh-khare-4019a53aa)"><img src="[https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)" /></a>
    <a href="[https://drive.google.com/file/d/1aFEIeNUV2R4P6N4c2AC_BD3ot24x5cP5/view](https://drive.google.com/file/d/1aFEIeNUV2R4P6N4c2AC_BD3ot24x5cP5/view)"><img src="[https://img.shields.io/badge/Resume-059669?style=for-the-badge&logo=googledrive&logoColor=white](https://img.shields.io/badge/Resume-059669?style=for-the-badge&logo=googledrive&logoColor=white)" /></a>
    <a href="[https://github.com/ansh35](https://github.com/ansh35)"><img src="[https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)" /></a>
  </p>

  <p align="center">
    <strong>Computer Science Graduate & Full-Stack Systems Developer</strong>. Focused on scalable multi-tenant SaaS systems, high-throughput microservices, and stateful multi-agent AI pipelines.
  </p>
</div>

---

### 💻 Core Competencies & Architecture Stack

| Domain | Core Technologies & Architecture Tools |
| :--- | :--- |
| **Frontend Architecture** | TypeScript, Next.js 15 (App Router, Server Actions), React, Tailwind CSS, Shadcn/UI |
| **Backend & Services** | Python (FastAPI, Pydantic), Node.js, Express.js, REST APIs, OAuth 2.0, NextAuth (JWT) |
| **Data Layer & ORMs** | PostgreSQL, MongoDB, SQLite, Prisma ORM (Connection Pooling, Schema Migrations) |
| **Agentic AI Systems** | LangChain, LangGraph (Cyclic Multi-Agent Graphs), Groq LPU API, Structured JSON Schemas |
| **Tooling & Operations** | Git, Postman, Linux Environments, Vercel Edge Runtime, Serverless Workflows |

---

## 🛠️ Deep-Dive Project Case Studies

### 1. 🚀 Nexora — Enterprise Multi-Tenant SaaS Workspace Platform
> **Architecture Focus:** Tenant Isolation, Role-Based Access Control (RBAC), and Optimized Data Fetching.  
> **Source:** [github.com/ansh35/Nexora](https://github.com/ansh35/Nexora)

* **Multi-Tenant Data Isolation:** Engineered clean data-layer separation ensuring users only access organization-scoped data; applied compound Prisma indexing across `tenantId` and resource primary keys for ultra-fast query lookups.
* **Granular RBAC Pipeline:** Designed strict session & token authorization middlewares to enforce Owner, Admin, and Member capability boundaries across internal workspaces.
* **Server-Side Rendering & Caching:** Built with Next.js App Router and React Server Components to eliminate layout shift, optimize Time to First Byte (TTFB), and cache repetitive tenant metadata.
* **State & Form Resilience:** Integrated Zod-validated server action schemas paired with Shadcn/UI for deterministic input parsing and zero runtime data-leak vectors.
* **Architecture Flow:** `[Client App]` → `[NextAuth JWT Session Gate]` → `[RBAC Middleware]` → `[Prisma ORM Layer]` → `[Tenant-Scoped DB]`

---

### 2. 🤖 AI Healthcare CRM Assistant — Autonomous HCP Interaction Engine
> **Architecture Focus:** Cyclic Agentic Graphs, Strict Schema Validation, and Low-Latency Clinical Logging.  
> **Source:** [github.com/ansh35/ai_first_crm_hcp_module_log_interaction_screen](https://github.com/ansh35/ai_first_crm_hcp_module_log_interaction_screen)

* **Cyclic Multi-Agent State Machine:** Architected a state graph using **LangGraph** to process unstructured Healthcare Professional (HCP) conversation transcripts through extraction, verification, and CRM-sync nodes.
* **Deterministic Structured JSON Output:** Utilized Pydantic schemas over Groq's low-latency inference engine to eliminate LLM hallucinations and enforce rigorous field validation (drug dosages, compliance markers, meeting metadata).
* **High-Throughput Backend Service:** Built async microservices with **FastAPI** leveraging connection pooling over SQLite/PostgreSQL to handle concurrent ingestion without blocking event loops.
* **Automated Task Scheduling:** Pipeline triggers automated next-step task creation, compliance flagging, and HCP sentiment classification directly into the CRM database.
* **Pipeline Flow:** `[Unstructured Raw Log]` → `[FastAPI Endpoint]` → `[LangGraph Cyclic Agents]` → `[Pydantic JSON Validation]` → `[CRM DB Commit]`

---

### 3. 📧 AI Email Cleaner — Scalable Mail Operations & Triage Agent
> **Architecture Focus:** OAuth 2.0 Security, Third-Party Batch Processing, and Privacy-Safe Categorization.  
> **Source:** [github.com/ansh35/AI_Email_Cleaner](https://github.com/ansh35/AI_Email_Cleaner)

* **Google OAuth 2.0 & Token Renewal:** Implemented granular Google API authorization flows with automated refresh token lifecycle management to prevent session interruptions.
* **Batch Metadata Processing:** Engineered a bulk email parsing queue using the Gmail API, optimizing API rate limits by consuming paginated metadata headers instead of raw message payloads.
* **High-Speed Inference Triage:** Batched non-confidential message headers into Groq LLM pipelines to cluster promotional blasts, newsletters, and transactional cold alerts in milliseconds.
* **Safe Bulk Sweeping:** Architected two-step verification safeguards and soft-delete queues to prevent accidental loss of high-priority communications.

---

### 4. ⚡ JSON-IQ — Developer Workspace & AST Syntax Analyzer
> **Architecture Focus:** Client-Side Parsing Performance, Real-Time AST Traversal, and Error Remediation.  
> **Live Demo:** [json-iq.vercel.app](https://json-iq.vercel.app) &nbsp;|&nbsp; **Source:** [github.com/ansh35/JSON_IQ](https://github.com/ansh35/JSON_IQ)

* **Zero-Lag Syntax Validation:** Built a high-performance in-browser JSON parser using Web APIs to perform instant formatting, minification, and recursive key-value tree traversing on megabyte-scale payloads.
* **AI Error Diagnosis:** Integrated Groq's low-latency API to intercept malformed syntax errors (dangling commas, missing quotes, token mismatches) and output instantaneous one-click automated fixes.
* **Responsive UI/UX:** Built with React, TypeScript, and clean custom styling for distraction-free developer workflows with immediate clipboard integration and export utilities.

---

## 📈 Engineering Cadence & Metrics

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=ansh35&show_icons=true&theme=tokyonight&hide_border=true&bg_color=09090b&title_color=38bdf8&text_color=94a3b8&icon_color=0ea5e9" height="155" alt="Ansh's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ansh35&theme=tokyonight&hide_border=true&background=09090b&ring=0ea5e9&fire=38bdf8&currStreakLabel=0ea5e9" height="155" alt="Ansh's GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=ansh35&layout=compact&theme=tokyonight&hide_border=true&bg_color=09090b&title_color=38bdf8&text_color=94a3b8" alt="Top Languages" />
</div>

---

## 🤝 Target Roles & Value Proposition

- **Roles:** Full-Stack Developer | Software Development Engineer (SDE) | Backend Developer
- **What I Deliver on Day 1:**
  - Production-ready TypeScript & Next.js architectures with strict type safety and zero structural tech debt.
  - Multi-agent orchestration workflows (LangGraph/LangChain) with deterministic JSON guardrails.
  - Clean API design, transactional ORM queries, and secure auth integration (OAuth / JWT).
- **Direct Connect:** [LinkedIn Profile](https://www.linkedin.com/in/ansh-khare-4019a53aa) &nbsp;•&nbsp; [Interactive Portfolio](https://anshkhare-portfolio.vercel.app/) &nbsp;•&nbsp; [Direct Resume](https://drive.google.com/file/d/1aFEIeNUV2R4P6N4c2AC_BD3ot24x5cP5/view)
