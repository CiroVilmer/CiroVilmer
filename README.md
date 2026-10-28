<div align="center">

### `Hi, I'm Ciro Vilmer` &nbsp;👋

**AI Engineer & FullStack Developer · AI Engineering student @ UDESA · Buenos Aires, Argentina** 🇦🇷

I build AI agents that hold up in production: assistants that answer from audited queries instead of guessing, WhatsApp agents wired into real ERPs, and the evals that prove they work. I also still ship full products end-to-end, from Postgres schemas to scroll-animated sites.

[![Portfolio](https://img.shields.io/badge/Portfolio-111?style=for-the-badge&logo=vercel&logoColor=white)](https://cirovilmer.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ciro-vilmer-b4727a174/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/ciro_vilmer/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cirov2005@gmail.com)

</div>

---

### 🧭 Now

- 🏢 Working part-time at **[Powercloud](https://www.linkedin.com/company/powercloud/posts/?feedView=all)**, building AI agents and internal tooling: an accounting assistant over an ERP and WhatsApp sales agents
- 🔬 Doing **NLP research at UDESA** on unmasking planners for diffusion language models in high-fertility languages like Spanish
- 🧩 Shipping **Claude Code tooling**, including an open-source mod that routes every subagent to the right model and effort
- 🛠️ Taking freelance work on the side: e-commerce, marketplaces and client sites in Argentina

---

### 🤖 AI systems & agents

| Project | What it does | Stack |
|---|---|---|
| **[jev-agent-router](https://github.com/CiroVilmer/jev-agent-router)** <sub>(open source)</sub> | Claude Code mod that picks the model and reasoning effort for each subagent from its task type (build, review, fix, explore). Rules first, classifier fallback on a 1 s budget. Benchmarked on 729 real subagent calls · 452 tests · v0.3.0. | TypeScript · Claude Code plugins |
| **ERP accounting assistant** <sub>(internal)</sub> | Answers accounting questions in Spanish over WhatsApp and a web console. Figures come only from saved, auditable queries: the LLM never writes SQL or does arithmetic. Graded against a golden set written by the accounting team; 900+ commits. | TypeScript monorepo · Next.js 16 · Postgres · AI SDK + OpenTelemetry · Odoo 18 · Docker |
| **WhatsApp sales agent** <sub>(IaaS client, internal)</sub> | Answers service questions with RAG, collects quote requests across 12 services and creates the leads in Odoo. Includes an end-to-end conversation harness and a measured answer verifier. | n8n · Qdrant · Chatwoot · Meta Cloud API · LiteLLM · Postgres |
| **dllm-planners** <sub>(UDESA research, ongoing)</sub> | A shared decode harness and trace viewer for comparing unmasking planners on diffusion LMs (LLaDA, Dream, Fast-dLLM), with parity tests against each model's reference generator. | PyTorch · FastAPI · Next.js |
| **[Prompty](https://prompty-ashen-alpha.vercel.app)** | AI listing optimizer for Mercado Libre, built at the Anthropic × Kaszek Hackathon, where it won 🥇 **1st place in the e-commerce track**. | Next.js 16 · FastAPI · Claude · DSPy + MIPROv2 |

---

### 🧰 Stack

**AI & Agents**

![AI SDK](https://img.shields.io/badge/AI_SDK-000?style=flat-square&logo=vercel&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![DSPy](https://img.shields.io/badge/DSPy-EE4C2C?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Whisper](https://img.shields.io/badge/whisper.cpp-412991?style=flat-square)
![Replicate](https://img.shields.io/badge/Replicate-000?style=flat-square&logo=replicate&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Remotion](https://img.shields.io/badge/Remotion-0B84F3?style=flat-square)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-000?style=flat-square)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)

**Infra & Testing**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square)

---

### 📊 GitHub

<div align="center">

![Ciro's GitHub stats](https://github-readme-stats.vercel.app/api?username=CiroVilmer&show_icons=true&hide_border=true&count_private=true&theme=transparent)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CiroVilmer&layout=compact&hide_border=true&theme=transparent)

</div>

---

<div align="center">

**Open to AI engineering roles, freelance work and collaborations** &nbsp;·&nbsp; Based in Buenos Aires, working worldwide.

_Let's build something._

</div>
