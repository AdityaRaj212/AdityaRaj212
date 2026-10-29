<h1 align="center">Aditya Raj</h1>

<p align="center">
  <b>Backend Software Engineer @ Pattern</b> &nbsp;·&nbsp; IIT Kharagpur '26
  <br/>
  Reliable APIs, marketplace integrations, and distributed systems on AWS
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aditya-raj-shit/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:adityaraj212.work@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.bagstack.tech"><img src="https://img.shields.io/badge/Bagstack%20(live)-111111?style=flat-square&logo=render&logoColor=white" alt="Bagstack (live)"/></a>
</p>

---

### What I do

I build and run TypeScript services on AWS that connect [Pattern](https://pattern.com) to marketplaces including Walmart, Shopify, eBay, Rakuten and Bol. Most of my work is making those integrations hold up under real traffic.

**Recent production work**

- **Order cancellation across 4 marketplaces**: eligibility checks, reason mapping and normalized errors, shipped in 5 PRs
- **Root-caused recurring 5xx errors** on a returns endpoint: a date parameter was pulling full order history, so requests took 8–10 s and some exceeded the 25 s timeout
- **Fixed Shopify polling outages of up to 50 min**: daily-rotated tokens were cached for an hour; the connector now refreshes on `401`
- **Cut ~3,300 failing eBay calls/day** that were draining the rate limit
- **Guardrails for AI coding agents** in Terraform repos: blocking TFLint, an OPA policy against wildcard IAM, lockfiles

---

### Selected projects

| | |
|---|---|
| **[Bagstack](https://github.com/AdityaRaj212/bagstack)** · [live](https://www.bagstack.tech) | Multi-account finance ledger. All money in integer minor units, passwordless OTP auth (hashed, rate-limited), LLM statement parsing gated by deterministic validation. 23 Vitest tests, multi-stage Docker.<br/><sub>Next.js · TypeScript · SQLite/Turso · Docker</sub> |
| **OakCapital** · [backend](https://github.com/Azad-Technology/Opensoft-26-Backend) · [frontend](https://github.com/Azad-Technology/Opensoft-26-Frontend) | Trading platform. C++ limit order book at **1.4M+ orders/sec**, linked into a Go backend via CGO with per-symbol mutex sharding; live market data over WebSockets + Redis Streams. **Opensoft 2026 Silver, team captain.**<br/><sub>C++ · Go · Redis · PostgreSQL · React</sub> |
| **[Mindflix](https://github.com/Azad-Technology/Opensoft-25-backend)** | AI-powered employee well-being platform. **Opensoft 2025 Bronze.**<br/><sub>Python · FastAPI</sub> |

### Currently building

- **Durable workflow engine**: Postgres-backed, worker leases, retries with backoff, sagas, dead-letter queue, signed webhook delivery; chaos-tested against worker and DB crashes. <sub>Java 21 · Spring Boot · PostgreSQL · k6</sub>
- **Safe text-to-SQL agent**: read-only execution, cost limits, audit logging, red-teamed against prompt injection; evaluated on BIRD. <sub>Python · PostgreSQL · Gemini</sub>

---

### Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-1f2328?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/> <img src="https://img.shields.io/badge/Go-1f2328?style=flat-square&logo=go&logoColor=white" alt="Go"/> <img src="https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/C%2B%2B-1f2328?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <br/>
  <img src="https://img.shields.io/badge/Node.js-1f2328?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/> <img src="https://img.shields.io/badge/Spring%20Boot-1f2328?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"/> <img src="https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/PostgreSQL-1f2328?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Redis-1f2328?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <br/>
  <img src="https://img.shields.io/badge/AWS-1f2328?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/> <img src="https://img.shields.io/badge/Terraform-1f2328?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/> <img src="https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/GitHub%20Actions-1f2328?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Datadog-1f2328?style=flat-square&logo=datadog&logoColor=white" alt="Datadog"/>
</p>
