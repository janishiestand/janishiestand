# Janis Hiestand

AI and full-stack software engineer in Zürich. I build and run production systems end to end, from LLM pipelines and data models to payments and operations. My two SaaS products, for financial research and legal contracts, use agentic tool use, RAG, evals and MCP servers.

## Production systems

### [ThesisCheck](https://thesischeck.io) · [sample report](https://thesischeck.io/sample-report)

ThesisCheck tests investment theses against primary filings from SEC EDGAR, LSE, ASX and EDINET and drops any claim it cannot match to an exact source passage. It has published a growing [library of reports](https://thesischeck.io/teardown) on public companies, and each one was checked automatically before it went live, including that it cites dated primary filings both for and against the thesis. Its remote MCP server is listed in the Official MCP Registry.

TypeScript · Next.js · Vercel AI SDK · Trigger.dev · PostgreSQL

### [InkDraft](https://inkdraft.io) · [examples](https://inkdraft.io/examples)

InkDraft turns sales-call transcripts into proposals, contracts and NDAs, then handles review, e-signature and payment. It uses RAG over each customer's own knowledge base, ties every commercial term to its place in the transcript, and calculates prices in code instead of taking them from the model.

TypeScript · Next.js · Prisma · PostgreSQL (pgvector) · Trigger.dev · Stripe

## Experience

I run both products through Hiestand Digital, my own company. From December 2025 to June 2026 I was a Senior Software Engineer on contract at Ante Digital, delivering AI automation with n8n and Trigger.dev for clients in healthcare recruitment, wealth advisory, real estate and media. Before that I was a Software Developer at Macos Software AG, where I worked on a large Swiss pension platform with 40 years of history, in C#, .NET 8 and Entity Framework.

The production repositories for ThesisCheck and InkDraft are private.

[Hiestand Digital](https://hiestanddigital.ch) · [LinkedIn](https://www.linkedin.com/in/janishiestand/)
