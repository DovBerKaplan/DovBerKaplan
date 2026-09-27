## DovBer Kaplan
Modules extracted from production self-hosted systems I've been running privately. The full stacks stay closed — these are the pieces that can stand alone.

I build Telegram bot infrastructure and content-based recommenders
that run on your own Postgres — no rented APIs on the hot path.

### Extracted & open-sourced
- **[cine-rec-engine](https://github.com/DovBerKaplan/cine-rec-engine)** — recommendation engine pulled out of a live media system: 22-feature learned scorer, multi-seed, saga-aware, BYO embeddings. Same code serves production daily.
- **[tg-session-gateway](https://github.com/DovBerKaplan/tg-session-gateway)** — born from bot deploys that kept killing Telegram sessions: session persistence, FloodWait backoff, crash-safe update queue.

### Stack
Python · PostgreSQL / pgvector · Docker · FastAPI · PyTorch · Redis
