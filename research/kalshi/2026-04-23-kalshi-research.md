# Kalshi Nightly Research Brief — 2026-04-23

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
The gap between professional quantitative research and retail trading is narrowing faster than most realize. If you can synthesize the mathematics of convergence and the architecture of automated execution before the rest of the market prices that knowledge in, you have found your edge.

Welcome to the April 23rd research digest. As we look at the current state of Kalshi and the broader prediction market ecosystem, we are seeing a fascinating convergence of three distinct worlds: high-level academic theory (arXiv), open-source infrastructure (GitHub), and massive capital inflows. 

To the untrained eye, a paper on "Bilinear Objectives" or a TypeScript repository might look like noise. But for the smart trader, these are the blueprints for the next generation of alpha. Let’s walk through the findings and build some intuition on how to use them.

## 1. The Infrastructure Layer: The "CCXT" Moment for Prediction Markets

In the world of crypto trading, CCXT became the industry standard by providing a unified API for dozens of exchanges. We are seeing that exact evolution happen now for prediction markets.

The most significant development here is the emergence of **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)**. Described as the "CCXT for prediction markets," this TypeScript library provides a unified API for trading across Polymarket, Kalshi, and others. Why does this matter? Because alpha in 2026 is rarely found on a single platform; it is found in the *discrepancies* between platforms.

We are already seeing "practitioner" bots leveraging this unified approach to hunt for price gaps. Specifically:
* **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** and **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** are both targeting the BTC 15-minute markets, executing paired trades to exploit price differences between Kalshi and Polymarket.
* For those looking at momentum rather than arbitrage, **[Razzleberryss/AstroTick](https://github.com/Razzleberryss/AstroTick)** provides an interesting blueprint, using orderbook skew and momentum signals to automate BTC contracts.

**The Intuition:** When the tooling moves from "custom scripts for one site" to "unified APIs for the whole sector," the speed of arbitrage increases. The window to manually spot a price difference is closing; the game has moved to the millisecond level.

## 2. The Theoretical Layer: Connecting the Math to the Market

This is where most retail traders stop reading, but it's where the real edge is hidden. The recent arXiv uploads suggest that the "math of the house" is evolving. I’ve categorized these by how they apply to your trading.

### On Prediction Market Dynamics and AI
We are seeing a push to understand if AI can actually "deduce" physical laws or if it's just interpolating data. The paper **"Autonomous Emergence of Hamiltonian in Deep Generative Models"** ([2604.20821v1](https://arxiv.org/abs/2604.20821v1)) asks an epistemological question: do these models memorize, or do they understand? For a trader, the answer determines whether an AI-driven signal is a reliable lead or a lagging indicator of a trend.

Similarly, **"ParetoSlider: Diffusion Models Post-Training for Continuous Reward Control"** ([2604.20816v1](https://arxiv.org/abs/2604.20816v1)) discusses moving away from single-scalar rewards toward multi-criteria control. In trading terms, this is the difference between optimizing for "profit" and optimizing for "risk-adjusted return across multiple constraints."

### On Binary Option Pricing and Convergence
If you trade binary contracts, you are essentially trading a probability that converges to 0 or 1. The paper **"Solving Minimax Problems with Bilinear Objectives with ADMM"** ([2604.20832v1](https://arxiv.org/abs/2604.20832v1)) explores how to find saddle points in concave-convex functions. While dense, this is the fundamental math behind how market makers price "fair value" in a competitive environment.

Furthermore, the work on **"Dynamic Construction of the Lovász Local Lemma"** ([2604.20836v1](https://arxiv.org/abs/2604.20836v1)) regarding local search algorithms and adaptive adversaries is highly relevant to how bots react to "toxic flow" (informed traders) in a dynamic market.

### On Tail Risk and Event-Driven Trading
Tail risk isn't just a "black swan"; it's a mathematical property of the distribution. The paper **"Failure of ambient closed-set large-deviation upper bounds in entropic optimal transport"** ([2604.20827v1](https://arxiv.org/abs/2604.20827v1)) warns us that standard bounds on compact sets don't always extend to closed sets. In plain English: the "safety nets" we use to calculate maximum possible loss may fail in certain non-compact scenarios. 

For those tracking AI security risks, **"AVISE: Framework for Evaluating the Security of AI Systems"** ([2604.20833v1](https://arxiv.org/abs/2604.20833v1)) is a critical read. As AI becomes a primary driver of market movement, the "vulnerability" of the AI itself becomes a tradable event.

## 3. The Macro View: $21 Billion and the "Regulatory Gap"

Finally, we have to look at the numbers. Prediction markets have hit a massive scale, with monthly volumes reaching $21 billion. But volume alone isn't a strategy—the *source* of that volume is.

The synthesis of recent market data shows a persistent "regulatory gap" between Kalshi (US-regulated) and Polymarket (decentralized/offshore). This gap creates different participant compositions: one side may be dominated by institutional hedgers, while the other is driven by retail sentiment and crypto-native speculators.

This divergence is exactly why the arbitrage bots mentioned earlier exist. When the same event is priced differently because the "crowd" on one platform is fundamentally different from the "crowd" on the other, you have a structural inefficiency. 

However, a word of caution: both platforms implemented enhanced insider trading controls on March 23, 2026. This suggests that the "easy" alpha from information asymmetry is being squeezed,
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-04-23 via Conway's auto-publisher.*
