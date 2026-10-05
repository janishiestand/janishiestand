# Janis Hiestand

AI and full-stack software engineer in Zürich. I build and run production systems end to end, from LLM pipelines and data models to payments and operations. My two SaaS products, for financial research and legal contracts, use agentic tool use, RAG, evals and MCP servers.

## Production systems

### [ThesisCheck](https://thesischeck.io)

ThesisCheck tests investment theses against primary filings from SEC EDGAR, LSE, ASX and EDINET and drops any claim it cannot match to an exact source passage. It has published a growing [library of reports](https://thesischeck.io/teardown) on public companies, and each one was checked automatically before it went live, including that it cites dated primary filings both for and against the thesis. Its remote MCP server is listed in the Official MCP Registry.

TypeScript · Next.js · Vercel AI SDK · Trigger.dev · PostgreSQL

### [InkDraft](https://inkdraft.io)

InkDraft turns sales-call transcripts into proposals, contracts and NDAs, then handles review, e-signature and payment. It uses RAG over each customer's own knowledge base, ties every commercial term to its place in the transcript, and calculates prices in code instead of taking them from the model.

TypeScript · Next.js · Prisma · PostgreSQL (pgvector) · Trigger.dev · Stripe

## Experience

I run both products through Hiestand Digital, my own company. Earlier I delivered AI automation for agency clients and worked on a large Swiss pension platform in C# and .NET.

The production repositories for ThesisCheck and InkDraft are private.

[Hiestand Digital](https://hiestanddigital.ch) · [LinkedIn](https://www.linkedin.com/in/janishiestand/)
