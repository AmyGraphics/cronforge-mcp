# CronForge MCP Server ⏱️⚡🔄

Universal Autonomous Background Tasks, Distributed Cron, BullMQ & Queue Architecture Engine MCP Server for **Cursor, Claude Code, Windsurf, and Autonomous AI Agents**.

## 🌟 Core Capabilities:
- 👑 **Master 1-Shot Outcome Engine (`autonomous_background_job_and_queue_architect`):** Ingests any background task or webhook requirement and outputs a complete asynchronous architecture (production queue worker, exponential backoff retries, Redis idempotency deduplication, cron triggers, and dead-letter queue recovery) in one invocation.
- ⚙️ **Production Queue Worker & DLQ Generator (`generate_queue_worker_and_retry_policy`):** Builds BullMQ, Inngest, and Cloudflare Queue consumers with concurrency throttling and failed-job Slack/Sentry alerts.
- ⏰ **Natural Language Crontab & Cloudflare Scheduler (`generate_cron_scheduler_and_crontab`):** Converts plain English schedules into exact crontabs, Cloudflare `[triggers.crons]`, and Vercel Cron configs.
- 🛡️ **Exactly-Once Idempotency Guard (`build_idempotency_and_deduplication_guard`):** Generates Redis and KV deduplication middleware preventing double-billing and duplicate job triggers.
- 🪝 **Replay-Safe Webhook Receiver Pipeline (`design_webhook_consumer_with_replay_defense`):** Builds sub-50ms async webhook ingestion endpoints for Stripe, Shopify, GitHub, and Clerk.

## 🚀 Server URL
`https://cronforge-api.agentweb-hub.workers.dev/mcp`


## 🔴 NEW in v1.1 — Live Tool: `parse_cron_expression`

A real cron parser: validates any cron expression (including @aliases, names, ranges, lists, steps), explains every field, computes the next 5 real UTC run times by calendar simulation, and flags impossible schedules and DOM/DOW OR-semantics traps.

No API key needed — works out of the box.

## 💰 Pricing

**Start free — 10 requests/day, no signup, no card.** Upgrade only if it earns a place in your workflow.

| Plan | Price | Pay with |
|------|-------|----------|
| **Free** | $0 | 10 requests/day — no signup needed |
| **Pro** (this server only) | **$7.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |
| **All-Access Suite** (all 44+ servers) | **$14.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |

### 💳 Option 1 — Gumroad (PayPal & Credit Cards)

👉 **[amygraphics.gumroad.com/l/mcp-pro](https://amygraphics.gumroad.com/l/mcp-pro)** — select *Single MCP Server* ($7.99) or *All-Access Lifetime Suite* ($14.99). Instant license key delivery.

### 🪙 Option 2 — Solana USDC (instant, no account needed)

Send **$7.99 USDC** (single) or **$14.99 USDC** (all-access) to:

```
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```

Then POST your transaction signature to the `/verify-solana` endpoint to activate your lifetime license instantly.
