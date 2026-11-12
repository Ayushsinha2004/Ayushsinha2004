# Ayush Sinha

AI full-stack engineer in Mumbai. I build LLM products that run on real business data, and the backends and dashboards around them. For nearly 2 years I have worked remotely for teams in New Zealand, Ireland and the UK.

I'm looking for a full-time remote role with a US, UK or EU team. I can work your core hours.

**Case studies:** https://ayushsinha2004.github.io  
**Email:** ayusharyansinha21@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/ayusharyan-sinha-632641257

## Work I can talk about

| What | Result |
|---|---|
| Point-of-sale ingest for a 180-store restaurant rollout in New Zealand, rebuilt on S3, SQS FIFO and Fargate workers | p99 accept latency went from 13.3s to 1.63s in a 7-day load test, with 0 dead-lettered messages |
| Document AI for an Irish life-insurance brokerage (OCR, GPT extraction, validation agents, review dashboard) | 3,205 policies tracked in 7 months |
| Plain-English analytics over a 64k-order ERP mirror, where the model writes a whitelisted query plan instead of SQL | 70 of 74 questions answered in a hand-checked eval sweep |
| Day-to-day delivery with Claude Code agents, driven by written specs and reviewed by me before merge | 306 merged pull requests across 7 repositories in 4 months |

Most of that code is private client work. The case-study page explains the architecture of each one.

## Public code

- [signal-agent](https://github.com/Ayushsinha2004/signal-agent): a Python agent that reads hiring posts, researches each company, and drafts outreach where every claim cites its source. It has rules, evals, an LLM judge and a human review screen. Live demo linked in the repo.
- [weather-aware-truck-routing](https://github.com/Ayushsinha2004/weather-aware-truck-routing): Django and React app that ranks 3 truck routes by forecast weather at each checkpoint's arrival time, including hours-of-service stops. 108 backend tests in CI. [Live](https://weather-aware-truck-routing-65x1.onrender.com)
- [lendloop](https://github.com/Ayushsinha2004/lendloop): a neighbourhood tool-lending board built with Next.js, Clerk, Convex and n8n.
- [debug-skill PR #21](https://github.com/AlmogBaku/debug-skill/pull/21): a fix for a hang in dap, an open-source Go debugger CLI for AI coding agents. Every Node.js debug command hung because the child session was never read. The PR is open upstream.

## Stack

TypeScript, Python, SQL · Node.js, NestJS, Fastify, Django · React, Next.js · PostgreSQL with row-level security, Supabase, pgvector · AWS (CDK, ECS Fargate, SQS, S3, Lambda) · OpenAI and Claude APIs, structured outputs, tool calling, RAG, LLM evals · n8n · Claude Code and MCP
