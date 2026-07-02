# Trading Nightly Research Brief — 2026-07-02

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-07-02T02:30:54, run time 27.7s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 0,
  "top_symbols_7d": [],
  "side_breakdown_7d": {}
}
```

## 2. arXiv Papers (Last 60 Days)
- **Computationally Efficient Near-Optimal Control for Current Ripple Reduction and Optimization of Three-Phase Motors via LMIs** _(quantitative trading strategy)_
  [2026-07-01](https://arxiv.org/abs/2607.01215v1)
  The optimal control of three-phase permanent-magnet synchronous motors (PMSMs) is challenging due to their nonlinearity and the discrete nature of the control set. Existing approaches either rely on mixed-integer trajectory optimization or require computationally intensive value-iteration procedures. This paper proposes a Linear Matrix Inequality (LMI)-based method for approximating the infinite-h

- **All-out Attack: Optimal Block Withholding Under Pay-Per-Share Scheme** _(quantitative trading strategy)_
  [2026-07-01](https://arxiv.org/abs/2607.01209v1)
  Classical Block Withholding (BWH) attacks have been extensively studied in block-dependent reward schemes, where pool members are compensated upon a block discovery within the pool. However, most contemporary mining pools operate under share-based scheme wherein participants are paid immediately upon submission of valid shares. In this paper, we analyze BWH under Pay-Per-Share (PPS) and Full-PPS (

- **When large trades are not news: Liquidity tail risk and price discovery** _(quantitative trading strategy)_
  [2026-07-01](https://arxiv.org/abs/2607.01198v1)
  When is a large trade news, and when is it a liquidity shock? We study this question in a sequential competitive limit order book with asymmetric information. In our model, liquidity suppliers observe aggregate order flow but not its decomposition into informed demand and uninformed liquidity demand. We model uninformed order flow with Student-$t$ tails, interpreted as a reduced form for rare liqu

- **Distributed Containment of a Compromised Agent through Repulsive Cages** _(momentum crash risk)_
  [2026-07-01](https://arxiv.org/abs/2607.01230v1)
  UAV swarms and cyber-physical multi-agent systems are increasingly deployed in safety-critical missions that require coordinated motion, distributed decision making, and autonomy. A major security risk arises when a legitimate agent is hijacked and driven by adversarial high-level commands. Rather than focusing on detection and isolation of malicious agents, we exploit a structural property common

- **Multidimensional Risk Made Easy** _(momentum crash risk)_
  [2026-07-01](https://arxiv.org/abs/2607.01229v1)
  Suppose we want to assign a certainty equivalent--one number--to a multivariate risk. Which such assignments are law-invariant, monotone with respect to vector stochastic dominance, and invariant to independent background risk? I show that every such certainty equivalent is a positive mixture of scalar entropic certainty equivalents applied to positive projections of the vector risk. The same repr

- **Interpretation of the binned SNe Ia Master Sample data via a scalar quintessence component: phantom transition?** _(momentum crash risk)_
  [2026-07-01](https://arxiv.org/abs/2607.01199v1)
  We study a modified cosmological scenario for the late Universe, involving an evolutionary dark energy model associated with the dynamics of a self-interacting scalar field in a potential-dominated regime. Through the analogy with a fluid energy-momentum tensor, we introduce a viscous contribution to the scalar dynamics, accounting for effective non-equilibrium behaviour of the self-interacting sc

- **Measuring the Gap Between Human and LLM Research Ideas** _(mean reversion statistical arbitrage)_
  [2026-07-01](https://arxiv.org/abs/2607.01233v1)
  LLMs are increasingly used to brainstorm research ideas, but existing evaluations mostly judge individual ideas by novelty, feasibility, or expert preference. We instead ask: how far are current LLM-generated ideas from human researchers? To characterize this gap, we build a large-scale evaluation framework for ideation from high-quality human research papers. For each paper, we reverse-engineer a

- **Brownian ratchets and pumps universally simulate many-body active dynamics** _(mean reversion statistical arbitrage)_
  [2026-07-01](https://arxiv.org/abs/2607.01231v1)
  Active systems can exhibit a broad range of phenomena forbidden in equilibrium. Their dynamics are often specified by abstract local update rules, and it is generally unclear when the same behavior can arise from physically natural driving. Here we show that two simple driving mechanisms can universally simulate any local active dynamics in spin systems. The first is the familiar setting of a time

- **Touching and Feeling the Data: A Reusable Software Pipeline for Tactile Statistical Graphs in Accessible Education** _(mean reversion statistical arbitrage)_
  [2026-07-01](https://arxiv.org/abs/2607.01214v1)
  Statistical visualization is usually treated as a visual medium, but data can also be touched. Three dimensional printed tactile graphs let blind and low vision students feel distributions, trace trends, and explore relationships through direct haptic interaction. Yet classroom scale use remains limited because producing each graph in CAD software requires specialized skill and hours of manual wor

- **Distributed Containment of a Compromised Agent through Repulsive Cages** _(regime detection market)_
  [2026-07-01](https://arxiv.org/abs/2607.01230v1)
  UAV swarms and cyber-physical multi-agent systems are increasingly deployed in safety-critical missions that require coordinated motion, distributed decision making, and autonomy. A major security risk arises when a legitimate agent is hijacked and driven by adversarial high-level commands. Rather than focusing on detection and isolation of malicious agents, we exploit a structural property common

- **RepoRescue: An Empirical Study of LLM Agents on Whole-Repository Compatibility Rescue** _(regime detection market)_
  [2026-07-01](https://arxiv.org/abs/2607.01213v1)
  Open-source libraries and tools are widely reused, but compatibility maintenance is expensive. Once maintainers leave, useful repositories can stop working as runtimes and dependencies evolve. We study whether LLM agents can adapt old repositories to modern environments, a task we call compatibility rescue. Unlike bug repair, compatibility rescue starts from a repository that worked in its origina

- **Distill to Detect: Exposing Stealth Biases in LLMs through Cartridge Distillation** _(regime detection market)_
  [2026-07-01](https://arxiv.org/abs/2607.01208v1)
  Language models deployed in high-stakes roles can potentially favor certain entities, brands, or viewpoints, steering user decisions at scale. Such preferential biases can be introduced by any actor in the model's supply chain and are most dangerous when the model reveals its preference only on the relevant topic while behaving identically to its unmodified base on all other inputs. Recent work ha

- **Is One Layer Enough? Training A Single Transformer Layer Can Match Full-Parameter RL Training** _(deep learning volatility forecasting)_
  [2026-07-01](https://arxiv.org/abs/2607.01232v1)
  Reinforcement learning (RL) has become a central component of post-training large language models (LLMs), yet little is understood about how RL adaptation is distributed across transformer layers. Existing approaches typically update all model parameters uniformly, implicitly assuming that every layer contributes similarly to the gains obtained during RL post-training. In this work, we challenge t

- **Language-Critique Imitation Learning from Suboptimal Demonstrations** _(deep learning volatility forecasting)_
  [2026-07-01](https://arxiv.org/abs/2607.01225v1)
  Prior work on imitation learning from suboptimal demonstrations typically relies on compressed supervision signals such as confidence estimates, discriminator scores, or importance weights. These scalar signals are inherently limited, as they cannot explicitly express intermediate reasoning about task progress, failure modes, or corrective actions. We propose a language-critique framework for imit

- **AutoMem: Automated Learning of Memory as a Cognitive Skill** _(deep learning volatility forecasting)_
  [2026-07-01](https://arxiv.org/abs/2607.01224v1)
  Memory expertise is a learned skill: knowing what to encode, when to retrieve, and how to organize knowledge--a capacity known in cognitive science as metamemory. We bring this perspective to LLMs by treating memory management as a trainable skill. We promote file-system operations to first-class memory actions alongside task actions, letting the model itself decide how to manage its memory. This 

- **Is One Layer Enough? Training A Single Transformer Layer Can Match Full-Parameter RL Training** _(transformer financial time series)_
  [2026-07-01](https://arxiv.org/abs/2607.01232v1)
  Reinforcement learning (RL) has become a central component of post-training large language models (LLMs), yet little is understood about how RL adaptation is distributed across transformer layers. Existing approaches typically update all model parameters uniformly, implicitly assuming that every layer contributes similarly to the gains obtained during RL post-training. In this work, we challenge t

- **Brownian ratchets and pumps universally simulate many-body active dynamics** _(transformer financial time series)_
  [2026-07-01](https://arxiv.org/abs/2607.01231v1)
  Active systems can exhibit a broad range of phenomena forbidden in equilibrium. Their dynamics are often specified by abstract local update rules, and it is generally unclear when the same behavior can arise from physically natural driving. Here we show that two simple driving mechanisms can universally simulate any local active dynamics in spin systems. The first is the familiar setting of a time

- **Beta-Particle Transport and Thermalization in Kilonova Ejecta with Detailed Atomic Microphysics** _(transformer financial time series)_
  [2026-07-01](https://arxiv.org/abs/2607.01228v1)
  When two neutron stars collide, they eject material containing heavy nuclei formed by the rapid neutron capture process ($r$-process). As these nuclei decay, they power a bright optical/near-infrared transient known as a kilonova (KN). Modeling KN emission is a complex problem involving atomic opacities, radiation transport, and heating powered by the thermalization of radioactive decay products l

- **Is One Layer Enough? Training A Single Transformer Layer Can Match Full-Parameter RL Training** _(reinforcement learning portfolio)_
  [2026-07-01](https://arxiv.org/abs/2607.01232v1)
  Reinforcement learning (RL) has become a central component of post-training large language models (LLMs), yet little is understood about how RL adaptation is distributed across transformer layers. Existing approaches typically update all model parameters uniformly, implicitly assuming that every layer contributes similarly to the gains obtained during RL post-training. In this work, we challenge t

- **Language-Critique Imitation Learning from Suboptimal Demonstrations** _(reinforcement learning portfolio)_
  [2026-07-01](https://arxiv.org/abs/2607.01225v1)
  Prior work on imitation learning from suboptimal demonstrations typically relies on compressed supervision signals such as confidence estimates, discriminator scores, or importance weights. These scalar signals are inherently limited, as they cannot explicitly express intermediate reasoning about task progress, failure modes, or corrective actions. We propose a language-critique framework for imit

- **AutoMem: Automated Learning of Memory as a Cognitive Skill** _(reinforcement learning portfolio)_
  [2026-07-01](https://arxiv.org/abs/2607.01224v1)
  Memory expertise is a learned skill: knowing what to encode, when to retrieve, and how to organize knowledge--a capacity known in cognitive science as metamemory. We bring this perspective to LLMs by treating memory management as a trainable skill. We promote file-system operations to first-class memory actions alongside task actions, letting the model itself decide how to manage its memory. This 

- **Computationally Efficient Near-Optimal Control for Current Ripple Reduction and Optimization of Three-Phase Motors via LMIs** _(cryptocurrency trading)_
  [2026-07-01](https://arxiv.org/abs/2607.01215v1)
  The optimal control of three-phase permanent-magnet synchronous motors (PMSMs) is challenging due to their nonlinearity and the discrete nature of the control set. Existing approaches either rely on mixed-integer trajectory optimization or require computationally intensive value-iteration procedures. This paper proposes a Linear Matrix Inequality (LMI)-based method for approximating the infinite-h

- **When large trades are not news: Liquidity tail risk and price discovery** _(cryptocurrency trading)_
  [2026-07-01](https://arxiv.org/abs/2607.01198v1)
  When is a large trade news, and when is it a liquidity shock? We study this question in a sequential competitive limit order book with asymmetric information. In our model, liquidity suppliers observe aggregate order flow but not its decomposition into informed demand and uninformed liquidity demand. We model uninformed order flow with Student-$t$ tails, interpreted as a reduced form for rare liqu

- **Muon as a Residual Connection** _(cryptocurrency trading)_
  [2026-07-01](https://arxiv.org/abs/2607.01124v1)
  Muon has recently emerged as one of the most effective optimizers for training large neural networks, yet its empirical success has been explained from several different perspectives. In this paper, we propose a simple mechanistic interpretation: Muon can be understood as an implicit residual connection during training. Specifically, orthogonalizing the update can sacrifice some immediate gradient

- **AutoMem: Automated Learning of Memory as a Cognitive Skill** _(options volatility surface)_
  [2026-07-01](https://arxiv.org/abs/2607.01224v1)
  Memory expertise is a learned skill: knowing what to encode, when to retrieve, and how to organize knowledge--a capacity known in cognitive science as metamemory. We bring this perspective to LLMs by treating memory management as a trainable skill. We promote file-system operations to first-class memory actions alongside task actions, letting the model itself decide how to manage its memory. This 

- **Theoria: Rewrite-Acceptability Verification over Informal Reasoning States** _(options volatility surface)_
  [2026-07-01](https://arxiv.org/abs/2607.01223v1)
  When should an AI system's answer be trusted? Formal proof assistants offer certainty but cannot reach most of the problem distribution; scalar LLM judges offer coverage but produce opaque scores that cannot be audited after the fact and are subject to the same coherence issues as any LLM. We present Theoria, a verification architecture that closes this gap. A candidate solution is rewritten into 

- **Ink3D: Sculpting 3D Assets with Extremely Complex Textures via Video Generative Models** _(options volatility surface)_
  [2026-07-01](https://arxiv.org/abs/2607.01222v1)
  Recent 3D generative models can synthesize high-quality geometry but often struggle to reproduce intricate textures from reference images, largely due to the scarcity of large-scale 3D training data with rich surface appearance. In contrast, visual generative models are trained on datasets several orders of magnitude larger and excel at modeling complex visual patterns. Motivated by this gap, we i

- **Type IIB Axion--Dilaton Wormholes and the BPS Limit Hessian** _(factor investing alpha)_
  [2026-07-01](https://arxiv.org/abs/2607.01221v1)
  I revisit Type-IIB axion--dilaton Euclidean saddles in a specified axion charge sector. In that sector, the solution with $E=0$ is the BPS instanton, while $E&gt;0$ gives non-BPS wormholes with a smooth throat. The two cases solve the same radial equations but define different fluctuation problems. For the $E=0$ instanton, the Hamiltonian constraint, gauge quotient, charge-sector boundary conditio

- **FurnitureVLA: Learning Long-Horizon Bimanual Furniture Assembly with Vision-Language-Action Model** _(factor investing alpha)_
  [2026-07-01](https://arxiv.org/abs/2607.01212v1)
  Current work on robot furniture assembly mostly focuses on toy-scale settings or single-arm manipulation. We introduce FurnitureVLA, the first systematic study of real-scale bimanual furniture assembly using Vision-Language-Action models (VLAs). We formalize the task, develop a scalable simulation pipeline for expert data generation and evaluation, and build a VR teleoperation system for single-op

- **On a conjecture of Andrews and almost alternating sign patterns** _(factor investing alpha)_
  [2026-07-01](https://arxiv.org/abs/2607.01210v1)
  In this paper, we prove a sign phenomenon first observed by Andrews for certain $q$-series from Ramanujan's Lost Notebook. For three of the series considered by Andrews, namely $v_2(q)$, $v_3(q)$, and $v_4(q)$, we show that the coefficients are alternating in sign, with only a density-zero set of exceptions. Our approach yields precise asymptotic formulas for the coefficients via an adapted circle

## 3. GitHub Repos (Recently Updated)
- **[cikafeee/algorithmic-trading-backtest](https://github.com/cikafeee/algorithmic-trading-backtest)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-02)_
  📊 Analyze and validate trading strategies with a high-performance backtesting engine using PySpark, processing thousands of backtests on real market data.

- **[11Bhavin/Quant_Trading_Portfolio-](https://github.com/11Bhavin/Quant_Trading_Portfolio-)** ⭐ 0 · None _(updated 2026-07-02)_
  📈 Build and backtest automated trading strategies using Python to enhance your quantitative finance skills and explore the financial markets.

- **[RafaEngineer/strapsim_portfolio_similarity_metric](https://github.com/RafaEngineer/strapsim_portfolio_similarity_metric)** ⭐ 1 · PHP _(updated 2026-07-02)_
  📊 Calculate portfolio similarity metrics to enhance ETF alignment and optimize trading strategies in quantitative finance.

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Python _(updated 2026-07-02)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[richkuo/go-trader](https://github.com/richkuo/go-trader)** ⭐ 323 · Go _(updated 2026-07-02)_
  Crypto trading bot — backtesting, paper trading, live trading with risk management

- **[simeunchul/crypto](https://github.com/simeunchul/crypto)** ⭐ 0 · Python _(updated 2026-07-02)_
  Crypto auto-trading bot (Binance Futures) with PC desktop + Flutter mobile apps. MA-crossover swing strategy, backtest-verified cooldown unlock policy.

- **[ashikscreativemath-commits/Paldo-ALM](https://github.com/ashikscreativemath-commits/Paldo-ALM)** ⭐ 16 · Python _(updated 2026-07-02)_
  🧠 Build adaptive algorithmic trading bots using machine learning and custom logic for MetaTrader 5 scalping and swing strategies.

- **[cikafeee/algorithmic-trading-backtest](https://github.com/cikafeee/algorithmic-trading-backtest)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-02)_
  📊 Analyze and validate trading strategies with a high-performance backtesting engine using PySpark, processing thousands of backtests on real market data.

- **[OpenSourceAGI/ai-broker-investing-agent](https://github.com/OpenSourceAGI/ai-broker-investing-agent)** ⭐ 11 · Python _(updated 2026-07-02)_
  💱 Invest with news debate agents, 🤑 algorithmic entry/exit strategies, 💹 execute on Alpaca, 🔮 copy trade  Polymarket/Kalshi prediction markets 

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-07-02)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[cuijinkuo/quant-research-platform](https://github.com/cuijinkuo/quant-research-platform)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-01)_
  Engineering showcase of a private China A-share quant research platform — architecture docs, factor-gating walkthrough, sanitised evaluation outputs. Alpha code kept private by design.

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-07-01)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[Gzeu/quantluna](https://github.com/Gzeu/quantluna)** ⭐ 0 · Python _(updated 2026-07-02)_
  QuantLuna — Adaptive Kalman Filter pairs trading engine for crypto markets (spot + perpetual futures). Statistical arbitrage, cointegration testing, market-neutral strategies.

- **[El-Moatasem/robust-pairs-trading-synthetic-regimes](https://github.com/El-Moatasem/robust-pairs-trading-synthetic-regimes)** ⭐ 0 · Python _(updated 2026-07-02)_
  MScFE 690 capstone research codebase for ML-enhanced equity pairs trading, synthetic market-regime robustness testing, cointegration-based statistical arbitrage, ML trade filtering, and risk-aware bac

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-07-02)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-02)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-07-01)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
For retail traders with small accounts ($100–$1,000) in April 2026, the most actionable systematic strategies are **Pullback Trend Trading with Fair Value Gaps (FVG)** and **Swing/Momentum Trading** using volume confirmation, as these avoid the high capital requirements of pair trading and the complex regime modeling needed for crypto momentum that small accounts often lack the data to filter effectively [1][2]. Strategies like **equity pair trading** and **crypto momentum with regime filters** have significantly **DEGRADED** for small accounts in the last 6 months due to overcrowding and the high cost of data/execution required to maintain a statistical edge, making them crowded trades to avoid [2][7].

### 1. Crypto Momentum with Regime Filters (Modified for Small Accounts)
*Note: Pure regime-filtered crypto momentum is crowded and degraded for small accounts. The actionable edge is now a simplified "Volume-Confirmed Swing Momentum" strategy.*
- **Time Horizon:** Swing trading (3–7 days).
- **Entry Rules:** 
  - Identify an existing trend wave (not chasing tops/bottoms).
  - Entry on a pullback to a **Fair Value Gap (FVG)** or support zone.
  - Confirmation: Volume spike must be **2–3x normal average** preceding the move [1][2].
  - Confluence: Price must be near support with a decisive move through resistance [2][6].
- **Exit Rules:** 
  - Target: First target is the next logical liquidity pool (previous swing point); take 50% off here [5].
  - Second target: Run remaining 50% to a second liquidity pool.
  - Stop-loss: Logical place where analysis is wrong (e.g., below liquidity sweep for bullish trades) [5].
- **Position Sizing:** Risk **1–2%** of the account per trade [2].
- **Source:** The "Pullback Trend Strategy with FVG" and "CEST Framework" (Conditions, Entries, Stops, Targets) are the most relevant 2026 frameworks for small accounts [1].

### 2. Equity Pair Trading
- **Status:** **DEGRADED/CLOUDED** for small accounts. The edge has eroded due to institutional dominance and high transaction costs relative to small capital.
- **Recommendation:** Avoid this strategy. Instead, focus on **S&P 500 or Russell 2000 trend following** using simple indicators like the Golden Cross or Supertrend [4].
- **If forced to trade:** Use **Sector Rotation** (e.g., long best-performing sector, short worst) on ETFs, but note this requires significant capital for shorting [4].

### 3. Options Tail Hedges (Currently Cheap)
- **Status:** Small accounts ($100–$1,000) cannot effectively trade options tail hedges due to the high premium cost and margin requirements.
- **Actionable Alternative:** Use **Momentum Trading** on equities to capture upside, as the "tail hedge" edge is often crowded and expensive for retail [2].
- **Note:** There is no specific "cheap" tail hedge edge identified in recent papers for small accounts; the focus should be on **risk management** (1–2% risk per trade) rather than hedging [2].

### 4. Newly Discovered Edge (Papers & Twitter)
- **Edge:** **Small-Cap Stock Trading** with strict support/resistance rules.
- **Concrete Parameters:**
  - **Time Horizon:** Swing trading (days to weeks).
  - **Entry:** Buy only at **support zones**, not resistance (Core Rule of Momentum Trading Alliance) [6].
  - **Exit:** Target next liquidity pool; take 50% off at first target [5].
  - **Sizing:** Risk 1–2% per trade [2].
- **Source:** SSRN paper "Small-Cap Stock Trading Strategies for Retail Traders" shows risk-adjusted returns >0.8 Sharpe ratio in out-of-sample periods [10].
- **Twitter/Substack Insight:** The "CEST Framework" (Conditions, Entries

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-07-02 via Conway's auto-publisher.*
