# shieldspprt

Full-stack AI engineer. I build at the seam between LLMs and Solana, and I ship the whole thing: agents, APIs, and the frontend that wraps them.

Right now I am building SolHunt, tooling that helps people recover forgotten SOL, sweep dust, revoke risky approvals, and reclaim rent without giving up custody. I also turn that work into AI agent skills so a model can read wallet health and give plain, actionable advice instead of noise.

Open to full-stack AI engineering roles and small, useful teams.

## What I do
- Design and ship AI agents (RAG, evals, tool use) that solve real tasks, not toy demos
- Build full-stack apps in TypeScript with React up front and Bun or Node behind
- Ship on Solana: Solidity and Rust programs, wallet tooling, trustless recovery flows
- Automate the boring parts with scheduled agents, MCP servers, and CI

## Selected work
- **[SolHunt](https://github.com/shieldspprt/solhunt-recovery)**: recover forgotten SOL, sweep dust, reclaim rent, and revoke approvals without custody.
- **[solhunt-skill](https://github.com/shieldspprt/solhunt-skill)**: AI agent skill for wallet health checks and approval auditing.
- **[Yellex](https://github.com/shieldspprt/yellex)**: AI pickup-line game built around Solana legends and historical figures.

## Stack I reach for
TypeScript · React / Next.js · Bun / Node · Postgres / Prisma · Solana / Solidity / Rust · Docker · Cloudflare · AWS · GitHub Actions

## Find me
- X: [@solhuntdev](https://x.com/solhuntdev)

## Engineering Log

<!-- STREAK -->
*Live, automated full-stack AI engineering micro-lessons. 26 entries, 10-day streak (last: 2026-07-21).*
<!-- /STREAK -->

<!-- LOGS -->
  - 2026-07-21: [Stream partial JSON from LLMs with a tolerant parser so the UI updates token by token](entries/2026-07-21-slot2.md)
  - 2026-07-21: [Coalesce identical in-flight LLM requests to share one upstream call](entries/2026-07-21-slot1.md)
- 2026-07-21: [Stream tool-call results to the client instead of buffering the full response](entries/2026-07-21-slot0.md)
- 2026-07-20: [Eval-driven prompt design beats prompt engineering by feel](entries/2026-07-20-slot2.md)
- 2026-07-20: [Stream tool-call results to the client instead of buffering the full response](entries/2026-07-20-slot0.md)
- 2026-07-19: [Ship a typed tool layer so agents never guess a schema](entries/2026-07-19-slot2.md)
- 2026-07-19: [Keep your RAG retriever honest with a score floor](entries/2026-07-19-slot0.md)
- 2026-07-18: [Backend idempotency keys stop duplicate writes from retries](entries/2026-07-18-slot2.md)
- 2026-07-18: [Cache your LLM responses at the edge to cut cost and latency](entries/2026-07-18-slot1.md)
- 2026-07-17: [Design idempotent webhook handlers with a dedupe key](entries/2026-07-17-slot2.md)
- 2026-07-17: [Backend idempotency keys stop duplicate writes under retry storms](entries/2026-07-17-slot1.md)
- 2026-07-17: [Gzip your server-sent-event stream, or you pay 10x for tokens you never read](entries/2026-07-17-slot0.md)
- 2026-07-16: [Cache LLM tool-call schemas at the gateway, not per request](entries/2026-07-16-slot2.md)
- 2026-07-16: [Backpressure saves your LLM service when a downstream API throttles you](entries/2026-07-16-slot1.md)
- 2026-07-16: [Colocate compute with data to avoid shipping rows you never render](entries/2026-07-16-slot0.md)
- 2026-07-15: [A prompt cache turns repeat questions into instant, free hits](entries/2026-07-15-slot2.md)
- 2026-07-15: [Constrain LLM output with a JSON schema instead of parsing prose](entries/2026-07-15-slot1.md)
- 2026-07-15: [Order a composite Postgres index to match your query shape](entries/2026-07-15-slot0.md)
- 2026-07-14: [Bounded concurrency beats Promise.all for LLM batches](entries/2026-07-14-slot2.md)
- 2026-07-14: [Idempotency keys keep LLM retries from double-firing](entries/2026-07-14-slot1.md)
- 2026-07-14: [Deduplicate near-duplicate chunks before embedding to cut RAG cost and retrieval noise](entries/2026-07-14-slot0.md)
- 2026-07-13: [Retry LLM calls with jittered exponential backoff, not fixed sleeps](entries/2026-07-13-slot2.md)
- 2026-07-13: [Cut LLM cost and latency with prompt caching](entries/2026-07-13-slot1.md)
- 2026-07-13: [Make agent tool calls idempotent with a deterministic key](entries/2026-07-13-slot0.md)
- 2026-07-12: [Idempotent API endpoints with an idempotency key](entries/2026-07-12-slot2.md)
- 2026-07-12: [Streaming LLM tokens to the browser with the Fetch API](entries/2026-07-12-slot1.md)
<!-- /LOGS -->

*Updated automatically every 8 hours. Full archive in the entries folder.*
