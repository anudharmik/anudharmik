<div align="center">

# Anurag Dharmik

**Full-stack engineer who builds AI-powered products and automation systems**

I don't follow tutorials. I pick a problem, design a system, and ship it.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://portfolio-zeta-flame-88.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/anurag-dharmik-60655537b)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:anuragdharmik07@gmail.com)

3rd year CSE @ Ramdeobaba University · **Available for internships · Bangalore (immediate)**

</div>

---

## What I build

I focus on three things: products with real users, automation systems that run without supervision, and AI integrations that actually improve workflows — not just demo well.

My work spans the full stack. On the frontend: React with clean component architecture, protected routing, and real-time UI. On the backend: PostgreSQL with proper schema design, RLS policies, and Supabase Edge Functions for scheduled workflows. For AI: integrating Gemini API into productivity systems that generate actionable insights, not just summaries.

---

## Featured projects

### [FounderOS](https://github.com/anudharmik/founder-os) — AI productivity platform · [Live ↗](https://founder-dashboard-five.vercel.app)

A full-stack operating system for execution tracking. Built solo from schema design to deployment.

**The hard parts:**
- Designed multi-tenant PostgreSQL architecture with Row Level Security — auth enforced at the database layer, not the application layer
- Built automated email workflows using Supabase Edge Functions + Resend that trigger on overdue task detection without a persistent server
- Integrated Gemini AI to analyze task completion patterns and surface personalized productivity insights
- Built analytics dashboards with Recharts that visualize productivity trends across goals and projects

`React` `TypeScript` `Supabase` `PostgreSQL` `Gemini AI` `Resend` `TailwindCSS` `Vercel`

---

### [Automated Outreach Pipeline](https://github.com/anudharmik/outreach-pipeline) — B2B automation system

A production Node.js pipeline that automates B2B lead generation end-to-end. No UI — just a system that runs.

**Four-stage architecture:**
```
Ocean.io (company discovery)
  → Prospeo (decision maker identification by domain)
  → Prospeo (decision maker's verified email identification)
  → Brevo (email verification + outreach automation)
```

**What makes it non-trivial:**
- Each stage consumes the output of the previous — sequential dependency managed with async/await chains and typed data contracts between stages
- Failed contacts write to a retry queue rather than crashing the batch — re-entry happens at the failed stage, not from the beginning
- API clients wrapped in rate-limit handlers to prevent 429s on large batches
- Built for real use, not demonstration

`Node.js` `REST APIs` `API orchestration` `Error handling` `Workflow automation`

---

### [Job Application Tracker](https://github.com/anudharmik/job-application-tracker) — Full-stack CRUD · [Live ↗](https://job-application-tracker-seven-psi.vercel.app)

Full-stack app with Supabase Auth, protected routing, real-time PostgreSQL operations, and status workflow tracking. Built to manage an actual job search.

`React` `Supabase` `PostgreSQL` `JavaScript`

---

## How I think about engineering

> I care more about *why* a system is designed a certain way than whether it compiles. Most of my architecture decisions come from asking what happens when things go wrong — what if the API is down, what if two users hit the same record, what if the email fails to send. That thinking shapes how I structure code before I write it.

---

## Stack

```
Languages     JavaScript  ·  TypeScript (learning)  ·  SQL
Frontend      React  ·  TailwindCSS  ·  Recharts
Backend       Node.js  ·  Supabase Edge Functions  ·  REST APIs
Database      PostgreSQL  ·  Supabase  ·  RLS policies
AI / APIs     Gemini API  ·  Resend  ·  Ocean.io  ·  Prospeo  ·  Brevo
Deploy        Vercel  ·  Railway
```

---

## Currently

- Building deeper backend systems — REST APIs, auth from scratch, schema design
- Learning TypeScript & Express.js properly (not just adding types to JavaScript)
- Actively looking for a **full-stack or backend engineering internship in Bangalore**
- Available to join immediately

---

<div align="center">
<sub>Open to full-time conversations too. I work fast, I ask good questions, and I don't need hand-holding.</sub>
</div>
<!--
**anudharmik/anudharmik** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
