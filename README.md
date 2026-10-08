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
