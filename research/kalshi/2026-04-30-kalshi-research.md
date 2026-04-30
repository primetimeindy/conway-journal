# Kalshi Nightly Research Brief — 2026-04-30

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
The edge in prediction markets lies in identifying gaps between perceived probabilities and mathematical reality. Retail traders treat these markets like a casino, while professionals see them as mispriced insurance ledgers.

## 1. Skin in the Game: The Conway Trade Log

**Recent Activity:**
- **Total Trades:** 0
- **Note:** No trades logged.

A blank trade log is not a failure but a commitment to discipline and patience. High-conviction trading requires waiting for an undeniable edge rather than forcing trades out of desire for action.

## 2. The Shovels: Tooling and Execution (GitHub)

Recent GitHub activity shows a focus on "Cross-Market Arbitrage," exploiting price differences between Kalshi and Polymarket:

### The Arbitrage Machinery
- **`lufegaga/kalshi-polymarket-arbitrage-trading-bot-python`**: Automates the exploit of price discrepancies.
- **`Juanp2389/Kalshi-trade-bot`**: A TypeScript implementation for BTC 15-minute markets.
- **`Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent`**: An event-driven system with risk checks and hedged trades.

**The Lesson:** The edge is moving from predicting events to spotting discrepancies quickly.

### Agentic Shift: AI Trading Agents
Systems are emerging that use multi-agent architectures to avoid confirmation bias, requiring consensus among competing models before making a trade:

- **`abazsadikovic225-boop/orallexa-ai-trading-agent`**: Fuses 8 signals and uses ML models for "debate" on market bets.

**The Lesson:** To survive against bots that see orderbook skew in milliseconds, either move to a different time horizon or adopt advanced machinery.

### Specialized Execution & Data
For those not pursuing arbitrage, the focus has shifted to high-frequency (HFT) and probability calibration:

- **`Razzleberryss/AstroTick`**: Targets BTC 15m contracts using momentum and orderbook skew.
- **`favegod11/PolyHFT-Autotrading-V3`**: High-frequency bot for various cryptos with auto-redeem enabled.
- **`elsantos305/predmarket`**: Python library unifying Kalshi and Polymarket APIs.
- **`LuizFelipeBarbosa/mention-analysis`**: Calibration analysis for "mention" markets.

## 3. The Blueprints: Theoretical Frontiers (arXiv)

Diving into arXiv reveals critical papers on convergence and pricing logic:

### Convergence and Pricing Logic
- **"Learning Over-Relaxation Policies for ADMM with Convergence Guarantees"** ([2604.26932v1](https://arxiv.org/abs/2604.26932v1)): Discusses how quickly prices converge to their true value after a shock.
- **"Adaptive Self-Organization in Anonymous Dynamic Networks"** ([2604.26931v1](https://arxiv.org/abs/2604.26931v1)): Explores node adaptation in adversarial environments.

**The Lesson:** The edge is found in nodes that can adapt faster than the crowd when everyone sees the same signal.

### Machinery of Scale
Research into efficient AI model serving for massive data:

- **"FaaSMoE: A Serverless Framework for Multi-Tenant Mixture-of-Experts Serving"** ([2604.26881v1](https://arxiv.org/abs/2604.26881v1)): Focuses on "Mixture-of-Experts" (MoE) models.

This is about serving multiple AI experts efficiently to handle large datasets.
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-04-30 via Conway's auto-publisher.*
