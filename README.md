# Hi, I'm Ali Cakil

Software engineer in Madrid, focused on AI. I build LLM features and AI agents that run in production for real users, on 12 years of .NET and AWS: provider-agnostic LLM layers, tool-calling agents, evals and tracing, MCP servers.

[alicakil.com](https://alicakil.com) · [LinkedIn](https://www.linkedin.com/in/alicakil) · ali@alicakil.com

## Featured: Vitena

**[Vitena](https://vitena.care)** (founder, 2025–2026) is a practice-management platform for health and wellness professionals, with a public directory where clients find and book them. I built it end to end as the only engineer; it runs in production with real users, in 7 languages, on the web and Android.

- A provider-agnostic LLM layer: one completion interface with an adapter per provider, model and cost policy per task type, every call metered with its real cost
- Tool-calling agents in production: in-app support, a public pre-sales assistant and an admin agent on read-only SQL with hard limits
- 20+ LLM task types: meal-plan drafts, session notes, document reading with vision, voice-to-record capture, email and feedback triage
- Tracing at the adapter layer, a spend report by task type and an eval harness that runs whenever a prompt changes
- A public, read-only MCP server listed in the official MCP Registry (`care.vitena/directory`)
- A coding-agent pipeline: Claude Code sessions work through a task step by step, with one plan approval up front and deploys behind a permission gate
- Under it: .NET 10 on AWS Lambda, PostgreSQL with a schema per tenant, Angular with SSR, infrastructure as code with AWS CDK

The product code is private; I'm happy to walk you through it on a screen share.

## Skills

- **AI:** LLM integration, AI agents and tool calling, MCP servers, prompt engineering, RAG, LLM evals and tracing, OpenAI API, Claude Code (agentic development)
- **Backend:** C#, .NET 10, ASP.NET Core, Minimal APIs, EF Core, REST, CQRS, DDD, microservices, event-driven architecture
- **Cloud:** AWS Lambda, API Gateway, Step Functions, SQS, DynamoDB, AWS CDK, AWS SAM, Terraform, CI/CD
- **Data and front end:** PostgreSQL, SQL Server, Cosmos DB · Angular, TypeScript

AWS Certified Developer – Associate

## Earlier work

- **Social events and ticketing app** (freelance, 2022–2024): serverless on AWS (Lambda, Step Functions, Cognito), LLM-based parsing of event content, Stripe tickets with QR check-in
- **Enterprise web apps on AWS** (Jabil, 2022–2024): event-driven .NET services on Lambda, Step Functions, EventBridge, SQS and SNS; Fargate, DynamoDB, Glue and Athena
- **Warehouse management systems** (Genesis AS, 2015–2022): custom WMS and automated-storage software, route-planning and truck-loading algorithms
