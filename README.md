# Hi, I'm Ali Cakil

Software engineer in Madrid. I build AI features and the .NET and AWS systems behind them, end to end: product, backend, front end, infrastructure and the LLM layer.

[alicakil.com](https://alicakil.com) · [LinkedIn](https://www.linkedin.com/in/alicakil) · ali@alicakil.com

## Featured: Vitena

**[Vitena](https://vitena.care)** (founder, 2025–2026) is a practice-management platform for health and wellness professionals, with a public directory where clients find and book them. I built it end to end as the only engineer; it runs in production with real users, in 7 languages, on the web and Android.

- .NET 10 on AWS Lambda, PostgreSQL with a schema per tenant, Angular with SSR, infrastructure as code with AWS CDK
- A provider-agnostic LLM layer: one completion interface with an adapter per provider, model and cost policy per task type, every call metered with its real cost
- Tool-calling agents in production: in-app support, a public pre-sales assistant and an admin agent on read-only SQL with hard limits
- Tracing at the adapter layer, a spend report by task type and an eval harness that runs whenever a prompt changes
- A public, read-only MCP server listed in the official MCP Registry (`care.vitena/directory`)
- A coding-agent pipeline: Claude Code sessions work through a task step by step, with one plan approval up front and deploys behind a permission gate

The product code is private; I'm happy to walk you through it on a screen share.

## Earlier work

- **Social events and ticketing app** (freelance, 2022–2024): serverless on AWS (Lambda, Step Functions, Cognito), Stripe tickets with QR check-in, LLM-based parsing of event content
- **Enterprise web apps on AWS** (Jabil, 2022–2024): event-driven .NET services on Lambda, Step Functions, EventBridge, SQS and SNS; Fargate, DynamoDB, Glue and Athena
- **Warehouse management systems** (Genesis AS, 2015–2022): custom WMS and automated-storage software, route-planning and truck-loading algorithms

## Stack

C# · .NET 10 · ASP.NET Core Minimal APIs · EF Core · PostgreSQL · SQL Server · AWS (Lambda, Step Functions, SQS, DynamoDB, CDK, SAM) · Angular · TypeScript · LLM agents, tool calling, evals, MCP

AWS Certified Developer – Associate
