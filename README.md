<h1 align="center">Hi, I'm Kamran Moazim 👋</h1>
<h3 align="center">Backend & AI Engineer · AWS Bedrock, AgentCore, MCP, RAG · Spring Boot · FastAPI · Node.js</h3>
<p align="center">I build AI-powered backend systems on AWS, mostly for fintech and healthcare. Based in Lahore, Pakistan (UTC+5), working remotely.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kamran-moazim"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://x.com/KamranMoazim"><img src="https://img.shields.io/badge/@KamranMoazim-000000?style=flat-square&logo=x&logoColor=white" alt="X"/></a>
  <a href="mailto:kamrannaseer765@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
 </a>
</p>

## 🙋‍♂️ About me

- 💼 Software Engineer at **Complyport** (formerly Map Fintech), building **Polaris**, a financial and regulatory reconciliation platform
- ☁️ ~4 years across backend development, AWS architecture (CDK-first, zero-idle-cost serverless) and Generative AI
- 🤖 Day-to-day focus: **Amazon Bedrock, AgentCore + MCP, RAG pipelines** and private, no-egress AWS networking
- 🎓 BS Computer Science, PUCIT Lahore (CGPA 3.67)
- 📫 Open to **remote backend / AI engineering roles** and AWS GenAI consulting

## 💼 Experience

**Software Engineer · Complyport (formerly Map Fintech)** · Cyprus, remote · Nov 2025 to present
- Full-stack features for Polaris Reconciliation in Spring Boot + React/TypeScript on a strict controller → boundary → service → repository architecture
- Records comparison engine for reconciliation reporting across financial datasets
- Configurable file ingestion (CSV / XLSX / XML / JSON) with splitters and dynamic field mapping via SpEL
- ClickHouse as an optional, per-company analytical persistence layer alongside MariaDB
- Role-adaptive dashboards and analytics endpoints with RBAC, plus a Playwright end-to-end test suite

**Software Engineer · DocNow EHR** · Bellevue, WA, hybrid · 2024 to 2025
- Designed a MongoDB → ClickHouse ETL pipeline with Apache Kafka + Node.js for real-time change capture
- Built Apache Superset reports used by providers for clinical decision-making
- Optimised MongoDB aggregation pipelines and integrated third-party insurance APIs

## 🛠️ Open-source projects

<!-- Confirm each repo is public before pushing. Replace REPO-NAME where shown. -->

| Project | What it does | Built with |
|---|---|---|
| [aws-serverless-ai-patterns](https://github.com/KamranMoazim/aws-serverless-ai-patterns) | Deploy-ready AWS CDK reference patterns for serverless and GenAI workloads, designed for zero idle cost | CDK, Lambda, Bedrock, AgentCore, S3 Vectors |
| [serverless-mail-mcp](https://github.com/KamranMoazim/serverless-mail-mcp) | A fully serverless mail system with an MCP layer, so AI agents can read and send mail | SES, Lambda, S3, DynamoDB, MCP |

## ⚡ Selected work

Highlights from client and portfolio builds (code private):

- **MCP gateway beyond the 100-tool limit.** Amazon QuickSight caps MCP servers at 100 tools, and the client needed more. I built an AgentCore MCP Gateway with Cognito RBAC and semantic tool search, and exposed it through a two-tool `searchTools` / `invokeTool` proxy on AgentCore Runtime. Delivered with a 5★ review.
- **Large-scale RAG without an OpenSearch bill.** Serverless ingestion with S3 Vectors and Step Functions Distributed Map, plus DynamoDB-native vector search, all in CDK.
- **Multi-tenant RAG with document-level access control** in Spring AI + pgvector, using a grant-based permission model that cascades effective scope across folders and knowledge bases.
- **Browser automation at scale.** A multi-tenant SaaS running Playwright workers on ECS Fargate, driven by SQS and EventBridge Scheduler.
- **Phone-call analytics pipeline.** S3 → SQS → Transcribe → Comprehend → Bedrock (Claude) → DynamoDB, with an API Gateway front end.
- **HIPAA-aligned clinic operations platform** on FastAPI, Aurora Serverless v2, Cognito and KMS.
- **Live streaming with AI subtitles.** MediaLive → MediaPackage → CloudFront with Elemental Inference smart subtitles.
- **KnowledgeDesk, a RAG app built entirely on Cloudflare.** Workers, D1, R2, Queues, Workflows, Vectorize, hybrid search (FTS5 + vectors + reranker), Durable Object chat agents, and a remote MCP server with OAuth.


## 🚀 Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,py,fastapi,ts,nodejs,nestjs,express,prisma,react,nextjs&perline=11" alt="Languages and frameworks"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=aws,cloudflare,dynamodb,postgres,mysql,mongodb,redis,kafka,supabase,docker&perline=11" alt="Cloud, data and tools"/>
</p>

- **Backend:** Java 21, Spring Boot 3, Spring AI, Spring Batch, Hibernate, Liquibase, Keycloak · Node.js (NestJS, Express, Prisma) · Python (FastAPI)
- **Generative AI:** Amazon Bedrock, Bedrock AgentCore (Runtime, Gateway, Identity, Memory), MCP, RAG, Guardrails, Nova Sonic, S3 Vectors, pgvector
- **AWS:** CDK, Lambda, API Gateway, Step Functions, EventBridge, SQS, ECS/Fargate, Aurora Serverless v2, Aurora DSQL, DynamoDB, S3, Cognito, KMS, SES, VPC Lattice, CloudFront, Transcribe, Comprehend, Textract
- **Cloudflare:** Workers, D1, R2, KV, Queues, Workflows, Vectorize, Durable Objects, Workers AI
- **Data:** PostgreSQL, MariaDB/MySQL, MongoDB, DynamoDB, ClickHouse, Redis, Kafka
- **BI & testing:** Apache Superset, Metabase, Playwright
- **Frontend:** React, TypeScript, Next.js, Redux Toolkit, Ant Design

---

<p align="center">
  <b>Hiring for a remote backend or AI role?</b> <a href="https://www.linkedin.com/in/kamran-moazim">Connect on LinkedIn</a> or <a href="mailto:kamrannaseer765@gmail.com">email me</a>.<br/>
  <b>Need AWS or GenAI work done?</b> <a href="https://calendly.com/kamrannaseer765/30min">Book a 30-minute call</a>.
</p>
