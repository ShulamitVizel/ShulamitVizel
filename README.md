# Hi, I'm Shulamit Vizel 👋
 
**Full-Stack Developer · Cloud Infrastructure · Applied GenAI**
 
I build and operate the platform side of an employee wellness and resilience product — frontend, backend, data integrations, and the AWS infrastructure underneath it.
 
---
 
## What I'm working on
 
I'm a full-stack developer at **DriveTech**, working on **Drivezone**, a platform that helps organizations measure and support employee wellness and resilience.
 
My work spans three areas:
 
**Product development**
Frontend and backend for Drivezone (`drivezone_front` / `drivezone_back`). React with RTK Query on the client, Node.js and TypeScript on the server. Recent work includes the Inspiration & Enrichment library feature, and building an internal Kanban board for team task management.
 
**Data integrations**
Designing and building a connector framework that pulls data from the systems organizations already run — HR, ERP/CRM, shift management, and financial systems — and uses it to enrich employee resilience scoring. I chose to build a Zapier-inspired internal framework (webhook and API based, multi-tenant by `org_id`) rather than depend on a third-party automation layer, so tenant data boundaries and transformation logic stay under our control.
 
Because this pipeline handles employee and manager data, compliance is part of the design rather than an afterthought: Israeli Privacy Protection Amendment 13, GDPR, and HIPAA-adjacent handling requirements shape what gets ingested, stored, and exposed.
 
**Cloud infrastructure**
I own the AWS estate for both development and production — account structure under AWS Organizations, IAM roles and access boundaries, EC2, and cost control. One example: automated AWS Budget Actions that detach Bedrock access when spend crosses a threshold, so an experiment can't quietly burn a month of budget.
 
---
 
## Tech I work with
 
**Languages & runtimes** — TypeScript, JavaScript, Node.js, Python, Bash
 
**Frontend** — React, Redux Toolkit / RTK Query, working from Figma designs
 
**Backend & data** — REST APIs, webhook-based integrations, multi-tenant data modeling
 
**Cloud & DevOps** — AWS (Organizations, IAM, EC2, Budgets, Bedrock), Docker, CI/CD
 
**AI** — LLM-backed features on Amazon Bedrock, agent-style architectures, Claude Code as part of my daily development workflow
 
---
 
## Projects
 
**Learning platforms**
 
- **[AI-Learning-Platform](https://github.com/ShulamitVizel/AI-Learning-Platform)** (TypeScript) — a learning platform built around AI-assisted study flows
- **[learning-platform-frontend](https://github.com/ShulamitVizel/learning-platform-frontend)** (TypeScript) — the client side of the same system
- **[Yedidim-Final-Project](https://github.com/ShulamitVizel/Yedidim-Final-Project)** — full-stack final project
**Web applications**
 
- **[Mac-Online-Shop](https://github.com/ShulamitVizel/Mac-Online-Shop)** (JavaScript) — e-commerce application with catalog, cart, and checkout flow
- **[Cows and Bulls](https://github.com/ShulamitVizel/cows-and-bulls)** (TypeScript) — number-guessing game
**Containers & deployment**
 
- **[devops_mbj_frontend](https://github.com/ShulamitVizel/devops_mbj_frontend)** (Shell) — deployment scripting for frontend services
- **[devops_mbj_backend](https://github.com/ShulamitVizel/devops_mbj_backend)** (JavaScript) — backend infrastructure and containerization
- **[dockerHM](https://github.com/ShulamitVizel/dockerHM)** (JavaScript) · **[dockerProject](https://github.com/ShulamitVizel/dockerProject)** (HTML) — Docker containerization exercises
---
 
## How I like to work
 
I'm most useful where product and infrastructure meet: the features people actually use, plus the pipelines, permissions, and cost controls that keep them running. I'd rather ship something small that holds up in production than something ambitious that needs constant hand-holding.
 
Based in Israel. Working across Hebrew and English.
 
---
 
## 📊 GitHub Stats
 
![ShulamitVizel's GitHub stats](https://github-readme-stats.vercel.app/api?username=ShulamitVizel&show_icons=true&theme=radical)
 
---
 
📫 [GitHub](https://github.com/ShulamitVizel) · [Repositories](https://github.com/ShulamitVizel?tab=repositories)
