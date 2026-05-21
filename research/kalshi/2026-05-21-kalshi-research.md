# Kalshi Nightly Research Brief — 2026-05-21

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

This underscores the importance of disciplined patience.

## 1. Recent Developments

### GitHub: Building Blocks for Automation

*   **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)**: Unifies APIs for Kalshi and Polymarket, simplifying data integration.
*   **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)**: Publicly available snapshots of the Kalshi trading dashboard for backtesting.
*   **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)**: An AI-powered bot using Gemini. Vet thoroughly before deploying with real capital.
*   **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)**: Arbitrage bot focusing on BTC markets, highlighting ongoing innovation in liquid and well-followed markets.
*   **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)**: Emphasizes fee-aware position sizing and statistical arbitrage, crucial for small accounts.

### arXiv: The Academic Echo

Key themes include tail-decay harvesting and arbitrage strategies.

## 2. Strategy #1: Tail-Decay Harvesting - Patience is Rewarded

**What it is:** Buying very low-probability contracts early and selling them later as the market realizes the event isn’t a true longshot. The edge comes from time decay, overreaction to headlines, and longshot bias.

**Practical setup:**

*   **Entry price:** 1–15 cents
*   Prefer contracts where your “true odds” are probably underpriced by at least 20–30%.
*   Best if there are 30+ days to expiry with a visible information path reducing uncertainty.

**Exit rules:**

*   Take profits once the contract doubles or reaches roughly 2x your entry price.
*   Exit when the event becomes structurally less uncertain, even if the price hasn’t doubled.
*   If the market moves to 0.5–1.5 cents above your basis, scale out due to spread/fees.

**Position sizing (for a $100 account):**

*   Risk 1–3% of bankroll per idea ($1–$3 per position).
*   Buy 5–20 contracts depending on price and expiry.

## 3. Strategy #2: Cross-Venue Arbitrage – The Math Edge

**What it is:** Exploiting price mismatches between Kalshi and Polymarket, or across equivalent contracts on multiple venues.

**How to execute:** Convert both sides to probabilities. Look for cases where the implied probabilities sum to less than 1 after fees/spread.

**Practical rules:**

*   Your expected edge must be at least 2–3%.
*   The spread on both legs must be manageable.
*   Quick execution is essential.

## The Future of Kalshi Trading

Start experimenting with `predmarket` to streamline data collection and trading across Kalshi and Polymarket for long-term benefits.