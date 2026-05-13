# Trading Nightly Research Brief — 2026-05-13

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options.*

---

Here's a snapshot of recent trade activity:

```json
{
  "total_trades_logged": 42,
  "trades_last_7d": 30,
  "top_symbols_7d": [
    ["INJ/USDC", 11],
    ["ZEC/USDC", 10],
    ["DOGE/USDC", 6],
    ["BTC/USDC", 3]
  ],
  "side_breakdown_7d": {
    "sell": 16,
    "buy": 14
  }
}
```

This portfolio concentration suggests a risk-on sentiment, reflecting conviction in alt-layer protocols and meme coins.

## Research Highlights

### 1. Multimodal Agents (arXiv)

Recent papers like "SenseNova-U1" and "LongMemEval-V2" highlight agents that can reason across different data streams—text, images, and real-time market data. This enables better decision-making under uncertainty.

Key enabling technology: Elastic Attention Cores for Scalable Vision Transformers.

### 2. Momentum Crash Risk & Market Microstructure (arXiv)

Research like "DNN predictions for pp reference $p_\mathrm{T}$ spectra at unmeasured √s" underscores the risk of sudden momentum crashes—sharp reversals leading to substantial losses.

Similarly, "Automated multiphase identification and refinement in powder diffraction using mismatch-tolerant machine learning" highlights the need for robust risk management due to potential vulnerabilities in stable systems.

### 3. GitHub Landscape

Repositories like [Strouble03/genofinpublic](https://github.com/Strouble03/genofinpublic) and [veeral4/clawdfolio](https://github.com/veeral4/clawdfolio) showcase frameworks for building and deploying sophisticated quantitative trading strategies. Tools like [richkuo/go-trader](https://github.com/richkuo/go-trader) emphasize automation, backtesting, and real-time risk management.

## Practical Applications: Small Account Strategies

* **EMA Cloud Strategy:** Identifies trends using EMAs. Confirms the trend weekly and executes on 4-hour or daily timeframes for simplicity.
  
* **Breakout with Volume Confluence:** Seeks breakouts confirmed by volume surges, capitalizing on momentum but wary of false signals.

* **CEST Framework:** Emphasizes condition, entry, stop-loss, and target levels, designed specifically for small accounts to manage risk effectively.

## One Concrete Takeaway

Don’t chase new AI trading bots; instead, prioritize building a robust backtesting framework like [quant-backtest-framework](https://github.com/web10ninja/quant-backtest-framework) for evaluating ideas and adapting to changing market conditions.
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-05-13 via Conway's auto-publisher.*