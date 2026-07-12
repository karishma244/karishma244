<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=190&section=header&text=Karishma%20Jethwani&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Engineer%20%7C%20AI%20Systems%20%7C%20BIT%20Mesra%20CSE&descAlignY=58&descSize=14&animation=fadeIn" width="100%" />

### `she ships it, then explains why it won't break.`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karishma0141/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Knight%20%7C%20Top%203.32%25-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/karishma_jethwani_/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:karishmaj0141@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=karishma244&label=Views&color=6e40c9&style=flat-square)](https://github.com/karishma244)

</div>

## About Me

Full-stack engineer building production systems, not tutorials. B.Tech CSE at BIT Mesra (CGPA 9.1), with two internships and three shipped products spanning SaaS, video infrastructure, and AI-driven finance tools. Ranked in the **top 3.32% globally on LeetCode** (Knight, 1952) and **CodeChef 3★** — competitive programming keeps the fundamentals sharp; production work keeps them honest.

## Currently

- 🔭 Building **Vidmax** — a high-throughput video hosting SaaS with adaptive bitrate streaming
- 🧠 Deepening RAG pipelines, vector search, and agentic AI architectures
- 📈 Studying distributed systems design at scale
- 🌱 Open to SDE internships and full-time roles

---

## Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Backend & Data**
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404d59?style=for-the-badge&logo=express&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![NATS](https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white)

**AI / ML**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20Pipelines-6e40c9?style=for-the-badge)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## Experience

**Scaler — Frontend Developer Intern** · `May 2025 – Jul 2025`
Built a 40+ component React.js library on Design System principles, cutting duplication by 35% and lifting sprint velocity by 20%. Shipped JWT auth with refresh-token rotation and Redux Toolkit, eliminating 30% of auth bugs.

**Fiale Technology — AI Automation Developer** · `May 2024 – Jul 2024`
Designed n8n-based automation workflows eliminating 40% of manual client tasks, saving 120+ engineering hours/month. Built NLP sentiment-analysis models improving client decision-making efficiency by 35% across 5+ workflows.

---

## Engineering Decisions Worth Mentioning

Not every choice makes it into a bullet point — a few that actually mattered:

**Why 3-layer caching in Vidmax instead of just Redis?**
Redis alone handled hot data fine, but repeated cold reads during traffic spikes were hammering PostgreSQL. Adding an in-process LRU layer in front of Redis cut DB reads by 60% without adding infra cost — sometimes the fastest cache is the one that avoids a network hop entirely.

**Why NATS over a simple job queue in Vidmax?**
Video analytics events needed to fan out to multiple consumers (billing, usage stats, monitoring) without blocking the upload pipeline. NATS's pub-sub model let each consumer scale independently — a Redis-based queue would've coupled them.

**Why Convex over a traditional REST backend in Echo?**
Real-time chat and RAG retrieval needed low-latency reactive updates across tenants. Convex's built-in reactivity removed the need to hand-roll WebSocket state sync, which would've eaten a week just on infra instead of the actual RAG logic.

**Why JWT refresh-token rotation at Scaler, not just long-lived tokens?**
Long-lived JWTs were the source of the auth bugs I was fixing. Rotation meant a stolen token had a shelf life — a few extra requests per session, but 30% fewer auth-related incidents made it worth it.

---

## Featured Projects

### [Vidmax — Scalable Video Hosting SaaS](https://github.com/karishma244/vidmax)
High-throughput video hosting platform with multipart uploads, resumable chunking, and server-side validation.

**Key Features:** 3-layer caching (LRU → Redis → PostgreSQL) cutting DB reads by 60% · HLS adaptive bitrate streaming with FFmpeg · Async analytics via NATS reducing write pressure by 80% · 95% upload reliability at sub-200ms response time

**Tech:** `Node.js · NestJS · TypeScript · PostgreSQL · Redis · Docker · FFmpeg · NATS · AWS`

📂 **Repository:** [github.com/karishma244/vidmax](https://github.com/karishma244/vidmax)

---

### [Echo — Multi-Tenant AI Customer Support Platform](https://github.com/karishma244/echo)
B2B SaaS support platform with real-time chat, voice agents, and RAG-based retrieval — handling 1,000+ conversations.

**Key Features:** Organization-scoped RBAC across tenants · AI-assisted human handoff and automated ticket resolution · Convex real-time backend with AWS Secrets Manager securing 300+ knowledge files · Sentry monitoring with Gitflow CI/CD

**Tech:** `Next.js · Convex · Clerk · TypeScript · Vapi · LangChain · AWS`

📂 **Repository:** [github.com/karishma244/echo](https://github.com/karishma244/echo)

---

### [Wealth Wise — AI Personal Finance Platform](https://github.com/karishma244/wealth-wise)
Full-stack finance platform with Gemini-powered receipt scanning and expense categorization at 90%+ accuracy.

**Key Features:** Optimized SQL queries improving performance by 30% · Real-time financial dashboards · Clerk OAuth authentication · Automated monthly AI savings reports

**Tech:** `Node.js · Next.js · React · TypeScript · PostgreSQL · Gemini API · Clerk`

📂 **Repository:** [github.com/karishma244/wealth-wise](https://github.com/karishma244/wealth-wise)

---

## Achievements & Leadership

| Achievement | Detail |
|---|---|
| **LeetCode Knight** | Rating 1952 · Top 3.32% globally · Rank 28,029 |
| **CodeChef 3★** | Rating 1636 · Rank 12,423 |
| **Battle of Bytes — Winner** | 1st place among 200+ teams |
| **Genesis AI (AICTE) — Technical Contributor** | Helped secure ₹2 Lakh funding via image review & model evaluation |

## Impact Snapshot

| Metric | Context |
|---|---|
| 120+ hrs/month saved | AI automation workflows at Fiale Technology |
| 60% fewer DB reads | Multi-layer caching architecture, Vidmax |
| 1,000+ conversations handled | RAG-based support platform, Echo |
| 30% fewer auth bugs | JWT rotation + Redux Toolkit, Scaler |
| Top 3.32% globally | LeetCode competitive programming |

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=karishma244&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6e40c9&icon_color=6e40c9&text_color=c9d1d9&ring_color=6e40c9" height="175" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=karishma244&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6e40c9&text_color=c9d1d9" height="175" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=karishma244&theme=tokyonight&hide_border=true&background=0d1117&stroke=6e40c9&ring=6e40c9&fire=ff6b6b" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=karishma244&bg_color=0d1117&color=6e40c9&line=6e40c9&point=ff6b6b&area=true&hide_border=true" width="100%" />

</div>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karishma0141/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/karishma_jethwani_/)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/slow_shapes_05)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karishmaj0141@gmail.com)

*Open to SDE internships, full-time roles, and conversations about systems that scale.*

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=90&section=footer" width="100%" />
</div>
