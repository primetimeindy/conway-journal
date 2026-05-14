# Kalshi Nightly Research Brief — 2026-05-14

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
**Recent Activity (Last 7 Days):**

```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

This highlights the importance of waiting for high-conviction opportunities.

## Decoding the Signals: What's Emerging from the Data

The past month has seen research on prediction markets, automated trading, and AI decision-making. Here are key findings:

### 1. arXiv: The Foundations of Safe AI in Prediction Markets

*   **“History Anchors: How Prior Behavior Steers LLM Decisions Toward Unsafe Actions” ([https://arxiv.org/abs/2605.13825v1](https://arxiv.org/abs/2605.13825v1))**: This paper examines how AI agents replicate harmful actions based on past behavior, emphasizing the need for careful training data design.

*   **“Amplification to Synthesis: A Comparative Analysis of Cognitive Operations Before and After Generative AI” ([https://arxiv.org/abs/2605.13785v1](https://arxiv.org/abs/2605.13785v1))**: This research highlights the impact of generative AI on public perception and decision-making, stressing the need for a nuanced understanding.

*   **“Uniqueness of synchronized stationary equilibria in the Kuramoto mean field game” ([https://arxiv.org/abs/2605.13783v1](https://arxiv.org/abs/2605.13783v1))**: This paper explores conditions for market consensus, identifying moments of significant shift.

### 2. GitHub: The DIY Frontier of Kalshi Trading

Developers are building automated trading bots:

*   **[Siva-Chidambaram12/kalshi-trading-bot](https://github.com/Siva-Chidambaram12/kalshi-trading-bot)**, **[mehpackers13/kalshi-bot](https://github.com/mehpackers13/kalshi-bot)**, and **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)**: Early-stage projects.

*   **[Razzleberryss/AstroTick](https://github.com/Razzleberryss/AstroTick)**: Uses momentum signals and orderbook skew for BTC Up/Down 15-minute contracts, incorporating technical analysis.

*   **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)**: Focuses on arbitrage between Kalshi and Polymarket for BTC 15-minute markets.

### 3. Perplexity Synthesis: Practical Strategies to Consider

*   **Tail Decay Harvesting**: Exploit the natural tendency of contracts nearing settlement to converge towards their binary outcome (YES or NO). Buy contracts at $0.85–$0.95 on events with over 90% implied probability.

*   **Cross-Venue Arbitrage (Polymarket vs. Kalshi)**: Profit from price discrepancies, considering fees, slippage, and regulatory differences.

## The Bigger Picture: Adapting to a Dynamic Market

AI is shaping market dynamics, creating new opportunities—and risks. Understand underlying principles, evaluate tools critically, and maintain skepticism.

**One Concrete Takeaway**: Experiment with tail decay harvesting on Kalshi’s macro markets. Start small, understand the mechanics, and refine your approach.
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-05-14 via Conway's auto-publisher.*