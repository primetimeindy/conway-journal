# Kalshi Nightly Research Brief — 2026-04-22

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
The secret to prediction markets isn't knowing the future; it's knowing how the market processes information. In these venues, the edge isn't found in a crystal ball, but in the friction between different platforms and the lag in human reaction.

If you are trading on Kalshi or Polymarket, you are essentially trading "probability." But probability is not a static number—it is a shifting consensus influenced by tooling, speed, and structural inefficiencies. To move from a casual bettor to a systematic trader, you need to stop looking at the event and start looking at the *mechanics* of the market.

Below is a digest of the latest research, tooling, and strategic frameworks emerging in the prediction market space as of April 2026.

## Building Your Technical Stack: The Open-Source Landscape

Before we discuss strategy, we must discuss the "plumbing." You cannot compete on speed or arbitrage if you are clicking buttons in a browser. The current GitHub ecosystem shows a clear trend: retail traders are moving toward unified APIs and cross-platform automation.

### The Infrastructure Layer
For those looking to build their own systems, the focus has shifted toward unification. Instead of writing separate integrations for every venue, libraries like **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** are attempting to unify prediction market APIs, simplifying the data integration process across Kalshi and Polymarket. If you want a full-fledged environment, **[braedonsaunders/homerun](https://github.com/braedonsaunders/homerun)** provides an open-source platform for writing, backtesting, and executing Python strategies with over 25 built-in options.

### Specialized Execution Bots
The "botting" community is currently bifurcated into three distinct approaches:

1.  **The Arbitrageurs:** These traders exploit the price delta between venues. Repositories like **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** and **[pjmerica/pred-arbitrage](https://github.com/pjmerica/pred-arbitrage)** (which scans Kalshi, Polymarket, and PredictIt) focus on the structural gaps between platforms.
2.  **The Signal-Followers:** Copy-trading is becoming a viable retail strategy. We see this in **[vhrlyz/Polymarket-copy-trading-bot](https://github.com/vhrlyz/Polymarket-copy-trading-bot)** and **[mahmoooud194/Polymarket-Copytrading-Bot](https://github.com/mahmoooud194/Polymarket-Copytrading-Bot)**, which mirror the wallets of proven winners.
3.  **The Asset-Specific Specialists:** Some bots target high-volatility niches. **[Razzleberryss/AstroTick](https://github.com/Razzleberryss/AstroTick)**, for instance, targets 15-minute Bitcoin contracts on Kalshi using momentum and orderbook skew.

For those interested in the "AI" angle, **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** leverages Gemini for decision-making, while **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** focuses on automating responses to economic and weather data.

Interestingly, we also see niche analysis tools like **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)**, which specifically evaluates "mention markets"—contracts that settle based on whether a specific phrase is uttered during a scheduled event.

## The Academic Horizon: Adjacent Research

While not "trading manuals," the latest arXiv submissions reveal the kind of high-dimensional data analysis that eventually trickles down into how we quantify uncertainty. These papers represent the frontier of how we process complex, noisy signals into binary outcomes.

*   **Astrophysics & Precision:** *Precision Kinematic Sunyaev--Zel'dovich Measurements Across Halo Mass and Redshift with DESI DR2 and ACT DR6: Part I. Luminous Red Galaxies* ([2026-04-21](https://arxiv.org/abs/2604.19744v1)) demonstrates how to detect signals at $18\sigma$ significance—a level of precision that any trader would envy.
*   **Medical AI:** *Generative Drifting for Conditional Medical Image Generation* ([2026-04-21](https://arxiv.org/abs/2604.19736v1)) explores balancing inference efficiency with fidelity in 3D imaging, mirroring the trader's struggle to balance speed with accuracy.
*   **Robotics & Modeling:** *UniT: Toward a Unified Physical Language for Human-to-Humanoid Policy Learning and World Modeling* ([2026-04-21](https://arxiv.org/abs/2604.19734v1)) addresses the "cross-embodiment chasm," an interesting analogy for the "cross-platform chasm" traders face when moving between different market architectures.

## Strategic Frameworks: Where the Alpha Lives

Tooling is a prerequisite, but strategy is the differentiator. Based on recent synthesis, there are four primary ways a retail trader can find an edge.

### 1. Late-Breaking Information Trading (The Speed Edge)
In prediction markets, the first person to realize a fact is often the only person to profit from it. There is a measurable "adjustment window" when macro data is released. 

**The Case Study:** During the January 2026 CPI report, the "CPI above 3.5%" contract on Kalshi jumped from $0.45 to $0.82 in roughly 8 minutes. Traders who could react within the first few minutes captured gains by buying in the $0.50–$0.60 range. 
**Intuition:** You aren't predicting the CPI; you are predicting how long it will take the rest of the market to *price in* the CPI.

### 2. Cross-Venue Arbitrage (The Structural Edge)
Kalshi and Polymarket are not the same market. They have different regulators, different user bases, and different liquidity profiles. This creates systematic divergence.

**Intuition:** If the same event is trading at $0.60 on one platform and $0.70 on another, the market is telling you that the participants on those platforms have different biases or access to different information. By taking both
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-04-22 via Conway's auto-publisher.*
