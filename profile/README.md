<div align="center">

# Lucyn

**The AI Product Engineer that works inside your company.**

Lucyn continuously understands your codebase, developer behavior, and product direction
then actively participates in execution through guidance, planning support, and intelligent task orchestration.

![Build](https://img.shields.io/github/actions/workflow/status/lucyn-tools/lucyn/ci.yml?branch=main&label=CI&style=flat-square)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-100%25-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Powered by Claude](https://img.shields.io/badge/Powered%20by-Claude%20AI-D4A27F?style=flat-square)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Bot%20on-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

</div>

---

## What is Lucyn?

Lucyn is an AI Product Engineer embedded directly into your engineering organization. It ingests data from GitHub, Discord, and meetings to build a continuously updated picture of your codebase and team — then uses that context to send private feedback to developers, surface delivery risks to leadership, and suggest task assignments. Unlike passive dashboards that report what happened, Lucyn is designed to act. It serves engineering teams at every level: CEOs and CTOs who need real-time health signals, and developers who want direct, contextual guidance without surveillance.

---

## The Problem

| 👔 For Leadership | 🔧 For Developers | 🔄 For the Org |
|---|---|---|
| No real-time visibility into engineering health | Invisible work goes unrecognized | Insights from meetings are never acted on |
| Fragmented data across GitHub, Jira, Discord | Code feedback is delayed and reactive | Task assignment is slow and biased |
| Can't predict delivery risk until it's too late | Forced to self-promote to get recognized | No system understands code + people + product |

---

## How It Works

**🔍 Understands** — Ingests GitHub commits, PRs, meeting transcripts, and Discord conversations. Builds a continuously updated Engineering Knowledge Graph.
**🧠 Reasons** — Uses Claude to cross-reference codebase context, developer behavior, and business intent. Retrieves only the most relevant context via RAG.
**⚡ Acts** — Sends private PR feedback to developers, surfaces delivery risks to leadership, suggests task assignments, posts meeting summaries.

---

## The Three Surfaces

<table>
<tr>
<td width="33%" valign="top">

### 🖥️ Web App
**For:** CEOs, CTOs, PMs

AI chatbot + engineering health dashboard.
Ask anything about your org. See delivery
confidence, velocity trends, risk signals,
and developer workload — in plain English.

</td>
<td width="33%" valign="top">

### 💬 Discord Bot
**For:** Engineers, Tech Leads

Private, opt-in guidance agent.
Reviews your PRs, gives commit feedback,
answers technical questions — all in DMs.
Never public. Never punitive.

</td>
<td width="33%" valign="top">

### 📹 Meet Agent
**For:** Full Team

Joins your SCRUM and planning calls.
Extracts goals, blockers, and decisions.
Posts structured summaries back to the
dashboard. Nothing falls through the cracks.

</td>
</tr>
</table>

---

## Tech Stack

**Application** - ![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs) ![discord.js](https://img.shields.io/badge/discord.js-5865F2?style=flat-square&logo=discord&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)

**Infrastructure** - ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**AI** - ![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D4A27F?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square)

**Tooling** - ![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

---

## Roadmap

**Phase 1 — MVP (In Active Development)**
- [x] Monorepo architecture
- [x] Database schema (multi-tenant)
- [ ] GitHub ingestion pipeline
- [ ] Discord PR guidance bot
- [ ] Engineering health dashboard
- [ ] AI chatbot interface
- [ ] Task recommendation system (human approval required)

**Phase 2 — Coming Next**
- [ ] Google Meet agent
- [ ] Automated sprint summaries
- [ ] Burnout signal detection
- [ ] Cross-repo knowledge graph
- [ ] Predictive delivery confidence
- [ ] Jira / Linear integration

---

## Privacy & Trust

- All developer feedback is private — never visible to managers or peers
- No surveillance metrics — no keystroke tracking, no hours monitoring, no individual scores
- Data stays in your org — embeddings are org-scoped, never shared across customers
- Human override always — every AI suggestion requires human approval before action
- GDPR-compliant architecture by design

---

## Contributing

Lucyn is currently in private development. If you're interested in early access or want to be a design partner, reach out.

Built with ❤️ by the Lucyn team.
