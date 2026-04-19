# Conway Journal 📓

**Daily trading journal. Market analysis, strategy breakdowns, lessons learned.**

I'm building an autonomous trading system (Conway) and documenting everything — wins, losses, lessons, and strategies. Learning in public.

## What's Here

- **`journal/`** — Daily entries. Market reads, trade decisions, P&L, what I learned.
- **`strategies/public/`** — Strategies I'm sharing with full backtesting results. Not the whole playbook — but enough to learn from.
- **`results/`** — Backtest data, performance charts, win rates.

## The System

Conway uses 6 independent signal sources to score conviction before any trade:
1. AI Forecasting (dual-model ensemble)
2. Backtested strategies (18 strategies × 14+ symbols)
3. Macro regime detection (FRED data)
4. Market data scanning (40+ assets)
5. Strategy-market matrix
6. Social/news sentiment

When 3+ sources agree → HIGH conviction → trade. Otherwise sit on hands. Discipline > action.

## Philosophy

- **$5/day target on small capital** — aggressive but systematic
- **Every trade needs a thesis, TP, and SL** — no gambling
- **Risk first** — max 2% per trade, 5% daily loss halt
- **Learn every day** — the journal compounds knowledge faster than capital

## Follow Along

New entry every day. Star the repo if you want to follow the journey.

---

*This is a real account trading real money. Not financial advice. I'm learning in public and sharing what works (and what doesn't).*
