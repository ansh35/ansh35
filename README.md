<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:09090b,50:0284c7,100:09090b&height=220&section=header&text=Ansh%20Khare&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Engineer%20%7C%20Type-Safe%20Web%20Systems%20and%20Developer%20Tooling&descAlignY=58&descSize=18" width="100%" />

  <p align="center">
    <a href="https://anshkhare-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Live_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    <a href="https://www.linkedin.com/in/ansh-khare-4019a53aa"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
    <a href="https://drive.google.com/file/d/1aFEIeNUV2R4P6N4c2AC_BD3ot24x5cP5/view"><img src="https://img.shields.io/badge/Resume-059669?style=for-the-badge&logo=googledrive&logoColor=white" /></a>
    <a href="https://github.com/ansh35"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  </p>

  <p align="center">
    <strong>Computer Science Graduate & Full-Stack Systems Developer</strong>.<br />
    Specializing in modern TypeScript web architectures, multi-tenant SaaS platforms, developer tooling, and API automation pipelines.
  </p>
</div>

---

### 💻 Core Competencies & Architecture Stack

| Domain | Core Technologies & Architecture Tools |
| :--- | :--- |
| **Frontend Architecture** | TypeScript, Next.js 15 (App Router, Server Actions), React, Tailwind CSS, Shadcn/UI, Monaco Editor |
| **Backend & Services** | Node.js, Express.js, FastAPI, RESTful APIs, OAuth 2.0, NextAuth (JWT) |
| **Data Layer & ORMs** | Prisma ORM, MongoDB, SQLite, PostgreSQL (Data Isolation, Schema Migrations, Indexing) |
| **AI & Automation** | Groq LPU API, Structured JSON Parsing, LLM Context Pipelines |
| **Developer Tooling** | VS Code Extension API, Git, GitHub, Postman, Linux Environments, Vercel Edge Runtime |

---

## 🛠️ Featured Engineering Projects

### 1. 🔍 CommentGlow — Semantic Code Highlighter (VS Code Marketplace)
> **Published:** [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=commentglow.commentglow) &nbsp;|&nbsp; **Source:** [github.com/ansh35/CommentGlow](https://github.com/ansh35)  
> **Architecture Focus:** VS Code Decoration Lifecycle, Regex Tokenization, and Zero-Attack-Surface Security.

* **Semantic Comment Parsing:** Implemented dynamic regular-expression parsing engines to style single-line, block, and multiline comment markers across the VS Code Decoration API.
* **Least-Privilege Security Architecture:** Engineered with strict zero-attack-surface security boundaries—zero network access, zero external runtime permissions, and zero dynamic code evaluation.
* **Performance & Memory Hygiene:** Managed document-change subscription disposables to prevent event listener leakage and ensure 60 FPS typing responsiveness in heavy codebases.

---

### 2. 🚀 Nexora — Enterprise Multi-Tenant SaaS Workspace Platform
> **Live Demo:** [nexora-ak.vercel.app](https://nexora-ak.vercel.app/) &nbsp;|&nbsp; **Source:** [github.com/ansh35/Nexora](https://github.com/ansh35/Nexora)  
> **Architecture Focus:** Tenant Isolation, Role-Based Access Control (RBAC), and Optimized Data Fetching.

* **Multi-Tenant Data Isolation:** Engineered clean data-layer separation ensuring users only access organization-scoped data; applied compound Prisma indexing across `tenantId` and resource primary keys for ultra-fast query lookups.
* **Granular RBAC Pipeline:** Designed strict session & token authorization middlewares to enforce Owner, Admin, and Member capability boundaries across internal workspaces.
* **Server-Side Rendering & Caching:** Built with Next.js App Router and React Server Components to eliminate layout shift, optimize Time to First Byte (TTFB), and cache repetitive tenant metadata.
* **State & Form Resilience:** Integrated Zod-validated server action schemas paired with Shadcn/UI for deterministic input parsing and zero runtime data-leak vectors.
* **Architecture Flow:** `[Client App]` → `[NextAuth JWT Session Gate]` → `[RBAC Middleware]` → `[Prisma ORM Layer]` → `[Tenant-Scoped DB]`

---

### 3. 📧 AI Email Cleaner — Scalable Mail Operations & Triage Agent
> **Demo Walkthrough:** [Watch Video Demo](https://drive.google.com/file/d/1J_q7gsQEIEWfTLsRs7jVTbajLbHDWUpD/view?usp=sharing) &nbsp;|&nbsp; **Source:** [github.com/ansh35/AI_Email_Cleaner](https://github.com/ansh35/AI_Email_Cleaner)  
> **Architecture Focus:** OAuth 2.0 Security, Third-Party Batch Processing, and Privacy-Safe Categorization.

* **Google OAuth 2.0 & Token Renewal:** Implemented granular Google API authorization flows with automated refresh token lifecycle management to prevent session interruptions.
* **Batch Metadata Processing:** Engineered a bulk email parsing queue using the Gmail API, optimizing API rate limits by consuming paginated metadata headers instead of raw message payloads.
* **High-Speed Inference Triage:** Batched non-confidential message headers into Groq LLM pipelines to cluster promotional blasts, newsletters, and transactional cold alerts in milliseconds.
* **Safe Bulk Sweeping:** Architected two-step verification safeguards and soft-delete queues to prevent accidental loss of high-priority communications.

---

### 4. ⚡ JSON-IQ — Developer Workspace & AST Syntax Analyzer
> **Live Demo:** [json-iq.vercel.app](https://json-iq.vercel.app) &nbsp;|&nbsp; **Source:** [github.com/ansh35/JSON_IQ](https://github.com/ansh35/JSON_IQ)  
> **Architecture Focus:** Client-Side Parsing Performance, Real-Time AST Traversal, and Error Remediation.

* **Zero-Lag Syntax Validation:** Built a high-performance in-browser JSON parser using Web APIs to perform instant formatting, minification, and recursive key-value tree traversing on megabyte-scale payloads.
* **AI Error Diagnosis:** Integrated Groq's low-latency API to intercept malformed syntax errors (dangling commas, missing quotes, token mismatches) and output instantaneous one-click automated fixes.
* **Responsive UI/UX:** Built with React, TypeScript, and Monaco Editor for distraction-free developer workflows with immediate clipboard integration and export utilities.

---

## 💼 Industry Experience

* **Haldiram's — Operations & Data Coordination Intern**
  * Audited operational data flows across 10+ internal systems to identify process bottlenecks.
  * Developed custom data transformation and automation scripts that improved reporting turnaround times by 25%.
  * Maintained structured data validation pipelines ensuring data accuracy across enterprise coordination tasks.

---

## 🤝 Target Roles & Value Proposition

- **Target Roles:** Full-Stack Developer | Software Development Engineer (SDE-1) | Frontend / Backend Engineer
- **What I Deliver on Day 1:**
  - Production-ready TypeScript & Next.js architectures with strict type safety and zero structural tech debt.
  - Clean REST API design, transactional ORM schemas (Prisma), and secure session authentication (OAuth / JWT).
  - High-velocity feature shipping with focus on performance, edge cases, and code maintainability.
- **Direct Connect:** [LinkedIn Profile](https://www.linkedin.com/in/ansh-khare-4019a53aa) &nbsp;•&nbsp; [Interactive Portfolio](https://anshkhare-portfolio.vercel.app/) &nbsp;•&nbsp; [Email Me](mailto:khareansh075@gmail.com)
