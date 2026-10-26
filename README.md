<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:0f3460&height=180&section=header&text=Tyler%20Malone&fontSize=60&fontColor=e0e0e0&fontAlignY=38&desc=AI%20engineer%20%2F%20full-stack%20%2F%20agent%20systems&descSize=16&descAlignY=58&descColor=7c8ea0" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&pause=1200&color=4ECDC4&center=true&vCenter=true&width=600&lines=agent+harnesses+%2F+tool+use+%2F+MCP;RAG+%2F+memory+%2F+multi-agent+workflows;full-stack+product+around+the+agent" alt="Typing SVG" />

<br/>

[![Website](https://img.shields.io/badge/tmalone.dev-0f3460?style=for-the-badge&logoColor=white)](https://tmalone.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tylermmalone)
[![Email](https://img.shields.io/badge/tyler@contraptionsoft.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tyler@contraptionsoft.com)
[![USMC](https://img.shields.io/badge/U.S.%20Marine%20Corps%20'18–'22-8B0000?style=for-the-badge&logoColor=white)](https://www.marines.mil)

</div>

---

Full-stack and AI engineer who builds agent systems that run in production. I was the founding engineer at [WarTable.ai](https://wartable.ai), taking it from an empty repo to paying customers, and I'm a Marine Corps veteran with a 3.96 GPA in CS from Colorado State.

**Open to remote roles:** AI Engineer (agents and harnesses), Full-Stack, Backend, Software Engineer.

---

## what I'm building now

At [ContraptionSoft](https://contraptionsoft.com), my veteran-owned automation shop:

- **Order pipeline for a CNC machine shop.** Purchase-order entry went from about 20 minutes by hand to under 2. PDF parsing, Zoho Books over MCP, generated traveler documents. Every write to the client's books goes through human approval and an audit log.
- **Inbox triage agent.** A bigger model designed the email buckets from real mail, then a cheap classifier sorted 3,200+ threads for about $0.29. 70% archived, with a guard that keeps low-confidence mail in the inbox.
- **Team-chat agent with a cost gate.** A cheap model scores every message. The full agent only replies when the gate passes, with locked-down tools.
- **meeting-context.** An MCP server that gives agents meeting memory: one LLM pass per transcript, SQLite full-text search, tools for search, transcripts and action items.
- **This job search.** A Claude Code skill that pulls postings from job boards, scores them against a context bank of everything I've done, tailors a resume from facts only, and logs outcomes. I review everything and submit myself.

Self-hosted on a Hetzner VPS: systemd services, Caddy, Twilio and Telegram gateways, Vapi voice agents.

## before that

- **WarTable.ai, founding engineer.** Built Athena, the in-app agent: a custom harness with about 3,000 app integrations through Pipedream, per-tool MCP controls, RAG over users' docs (ChromaDB) and memory across conversations (Mem0). Also a concurrent multi-agent evaluator, Stripe usage billing, Google and Microsoft sign-in, and GCP infra and CI/CD across 3 repos. I found and fixed a cost-tracking bug that was missing most of our LLM spend, and added reconciliation against the provider.
- **HYVV, sole engineer.** Rewrote the product: Next.js frontend, Python/Flask backend on the OpenAI Agents SDK, pytest suite, CI and release deploys to Cloud Run.
- **Colorado State, research assistant.** Built the bibliography check for RamDesk, CSU's grading platform. It has run 36K+ integrity checks. Also robotics at the HAPI Lab: an autonomous Fetch robot demo with my own YOLO component.
- **U.S. Marine Corps, utilities engineer.** Planned and ran field power for a 200-person command element. Held the Operations Staff NCO billet as a Corporal.

## public bits

- [Pipedream](https://github.com/PipedreamHQ/pipedream/pull/19984): merged HighLevel contribution
- [chunky-radar](https://github.com/19tylermalone94/chunky-radar): Dwarf Fortress-style live flight tracker, pixel map and CRT UI
- [connect-4-online](https://github.com/19tylermalone94/connect-4-online): play Connect 4 against a neural network
- [malonedigs.com](https://github.com/ContraptionSoft/malonedigs.com): Next.js site for a local excavation business
- [euler-go](https://github.com/19tylermalone94/euler-go): Project Euler's first 100 in Go

---

## stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

![MCP](https://img.shields.io/badge/MCP-191919?style=flat-square&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel%20AI%20SDK-000000?style=flat-square&logo=vercel&logoColor=white)
![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI%20Agents%20SDK-412991?style=flat-square&logo=openai&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6366f1?style=flat-square&logoColor=white)
![Pipedream](https://img.shields.io/badge/Pipedream-2D6EFF?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square&logoColor=white)
![Mem0](https://img.shields.io/badge/Mem0-111111?style=flat-square&logoColor=white)
![Vapi](https://img.shields.io/badge/Vapi-5DFECA?style=flat-square&logoColor=black)

</div>

---

<div align="center">

![Claude Code](https://img.shields.io/badge/Claude%20Code-C17B49?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat-square&logo=openai&logoColor=white)

</div>

---

## stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=19tylermalone94&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4ECDC4&icon_color=4ECDC4&text_color=c9d1d9&rank_icon=github" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=19tylermalone94&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4ECDC4&text_color=c9d1d9&langs_count=6" />

<img src="https://github-readme-streak-stats.herokuapp.com?user=19tylermalone94&theme=github-dark-blue&hide_border=true&background=0d1117&ring=4ECDC4&fire=FF6B6B&currStreakLabel=4ECDC4" />

</div>
