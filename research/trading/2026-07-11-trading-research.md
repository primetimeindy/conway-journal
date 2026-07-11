# Trading Nightly Research Brief — 2026-07-11

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-07-11T02:33:17, run time 25.9s._

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
- **ZipDepth: Bringing Lightweight Zero-Shot Monocular Depth Anywhere, on Any Device** _(quantitative trading strategy)_
  [2026-07-09](https://arxiv.org/abs/2607.08771v1)
  Monocular depth estimation has seen remarkable progress through foundation models achieving robust zero-shot generalization, yet their computational demands place them far beyond the reach of embedded and mobile platforms. Lightweight alternatives exist, but have been developed almost exclusively within single-domain, self-supervised paradigms, failing silently under domain shift. We present ZipDe

- **Geometry and Gradient-based Partitioning for Panoramic Outdoor Reconstruction** _(quantitative trading strategy)_
  [2026-07-09](https://arxiv.org/abs/2607.08769v1)
  Scaling 3D Gaussian Splatting (3DGS) to large outdoor scenes is costly in both data acquisition and computation. Adopting panoramic images with equirectangular projection (ERP) can reduce capture effort via their full $360^{\circ}$ field of view, yet the resulting omnipresent visibility invalidates existing partitioning strategies that rely on local camera frustums, causing block-wise optimization

- **UniClawBench: A Universal Benchmark for Proactive Agents on Real-World Tasks** _(quantitative trading strategy)_
  [2026-07-09](https://arxiv.org/abs/2607.08768v1)
  The rapid development of large language models and multimodal large language models has accelerated the emergence of proactive agents capable of operating everyday tools and assisting users in real-world environments. However, existing benchmarks struggle to evaluate such agents effectively, as they often rely on sandboxed environments and single-turn evaluation paradigms. Moreover, their scenario

- **Internal pseudospin, lepton-number superselection, and neutrino--antineutrino coherence in massive neutral-fermion one-particle states** _(momentum crash risk)_
  [2026-07-09](https://arxiv.org/abs/2607.08739v1)
  At fixed three-momentum, massive Dirac neutrino one-particle states span a 4D space of particle--antiparticle identity and helicity. We show that helicity flip, charge conjugation, and their product close an internal $SU(2)$ pseudospin subalgebra within $SU(4)$, distinct from the Wigner little group. Its helicity generator is the lepton-number-weighted spin rotation $U_1=2LJ_2$. The lepton-number 

- **Tilted thin accretion disks in the full Kerr spacetime and their implications** _(momentum crash risk)_
  [2026-07-09](https://arxiv.org/abs/2607.08728v1)
  We derive a steady-state warped-disk equation in the full Kerr spacetime to study the tilt dynamics of a thin, viscous accretion disk around a spinning collapsed object. The formulation, based on Pringle's framework, remains valid for all values of the Kerr parameter $a$, thereby encompassing both Kerr black holes (BHs; $0 &lt; a \le 1$) and Kerr naked singularities ($a &gt; 1$). By incorporating 

- **Force convergence in Monte Carlo Lyman-alpha radiative transfer** _(momentum crash risk)_
  [2026-07-09](https://arxiv.org/abs/2607.08726v1)
  Monte Carlo radiative transfer (MCRT) is widely used to model Lyman-alpha (Lya) resonant-line transport, but convergence is difficult to assess in optically thick media where photons undergo many scatterings before escape. This is especially important for internal quantities such as radiative acceleration and the force multiplier, which depend on momentum deposition throughout the gas rather than 

- **Plaquette: A hardware-aware design platform for fault-tolerant quantum computers** _(mean reversion statistical arbitrage)_
  [2026-07-09](https://arxiv.org/abs/2607.08767v1)
  Hardware teams building fault-tolerant quantum computers (FTQCs) must decide which imperfections to suppress, and that decision requires the logical performance of the architecture under the device's actual noise. Hardware noise often departs from the stochastic Pauli models used by scalable stabilizer simulators: superconducting transmons leak out of the computational subspace, neutral atoms scat

- **Irreducible Geometry of Higher-Order Correlator Families** _(mean reversion statistical arbitrage)_
  [2026-07-09](https://arxiv.org/abs/2607.08761v1)
  Programmable quantum simulators are beginning to access correlators of increasing complexity, ranging from four-point out-of-time-ordered correlators to even higher-order many-body correlators. The theoretical framework for interpreting such data, however, remains comparatively underdeveloped. Although a variety of higher-order correlators can be constructed straightforwardly, their physical meani

- **Hockey stick $f$-divergences** _(mean reversion statistical arbitrage)_
  [2026-07-09](https://arxiv.org/abs/2607.08760v1)
  In this paper we give a systematic and unified treatment and extensions of various results on a new notion of quantum $f$-divergences defined from quantum hockey stick divergences, the theory of which has been developed recently in \cite{BHT_fdiv,HircheTomamichel_integral,LiuHircheCheng2025}. In particular, we consider non-normalized states and hockey stick $f$-divergences defined from more genera

- **Hockey stick $f$-divergences** _(regime detection market)_
  [2026-07-09](https://arxiv.org/abs/2607.08760v1)
  In this paper we give a systematic and unified treatment and extensions of various results on a new notion of quantum $f$-divergences defined from quantum hockey stick divergences, the theory of which has been developed recently in \cite{BHT_fdiv,HircheTomamichel_integral,LiuHircheCheng2025}. In particular, we consider non-normalized states and hockey stick $f$-divergences defined from more genera

- **Debris Disc Substructures Induced by Secular Planetary Perturbations** _(regime detection market)_
  [2026-07-09](https://arxiv.org/abs/2607.08750v1)
  Observations of debris discs have the potential to provide us with valuable information about massive planets perturbing them gravitationally. In this work, we explore the evolution of the azimuthally-averaged (or axisymmetric) surface density (ASD) -- a characteristic routinely derived from observations -- in a disc secularly perturbed by an inner planet. We develop detailed analytical understand

- **Deep Spectroscopic Follow-Up of Maisie's Galaxy -- A Typical Galaxy in the Early Universe** _(regime detection market)_
  [2026-07-09](https://arxiv.org/abs/2607.08749v1)
  The first several years of JWST observations have yielded surprisingly large numbers of bright $z&gt;10$ galaxies, with follow-up spectroscopy of many of these sources implying extreme star formation activity and/or AGN content. Here, we present a combination of two deep Cycle 3 NIRSpec G395M programs, totaling over 19 hours of exposure time, plus MIRI/LRS observations for one such high-redshift s

- **Wat3R: Underwater 3D Geometry Learning without Annotations** _(deep learning volatility forecasting)_
  [2026-07-09](https://arxiv.org/abs/2607.08772v1)
  Estimating 3D geometry in underwater environments presents unique challenges due to light attenuation, scattering, and the absence of large-scale, high-quality 3D annotations. Pioneering methods rely on massive dense annotations that are impractical in underwater settings. In this paper, we propose Wat3R, a cross-domain semi-supervised learning framework designed to adapt feed-forward 3D reconstru

- **Enhancing In-context Panoramic Generation via Geometric-aware Pretraining** _(deep learning volatility forecasting)_
  [2026-07-09](https://arxiv.org/abs/2607.08765v1)
  In this work, we present Canvas360, a two-stage framework for in-context panoramic generation that combines geometry-aware pretraining with downstream task-specific fine-tuning. To address the lack of large-scale, high-quality training data tailored to in-context panoramic tasks, we propose Canvas360Dataset, a collection of 1M high-quality paired panoramic samples for style transfer, inpainting, o

- **OpenCoF: Learning to Reason Through Video Generation** _(deep learning volatility forecasting)_
  [2026-07-09](https://arxiv.org/abs/2607.08763v1)
  Reasoning has become a core capability for large models, especially when reliable decisions require understanding logical consequences. Recent video generation models offer a reasoning path distinct from previous Chain-of-Thought (CoT): reasoning can unfold through temporally connected frames, known as Chain-of-Frame (CoF) reasoning. However, existing video generators are primarily trained on gene

- **ZipDepth: Bringing Lightweight Zero-Shot Monocular Depth Anywhere, on Any Device** _(transformer financial time series)_
  [2026-07-09](https://arxiv.org/abs/2607.08771v1)
  Monocular depth estimation has seen remarkable progress through foundation models achieving robust zero-shot generalization, yet their computational demands place them far beyond the reach of embedded and mobile platforms. Lightweight alternatives exist, but have been developed almost exclusively within single-domain, self-supervised paradigms, failing silently under domain shift. We present ZipDe

- **OPSD-V: On-Policy Self-Distillation for Post-Training Few-Step Autoregressive Video Generators** _(transformer financial time series)_
  [2026-07-09](https://arxiv.org/abs/2607.08766v1)
  We propose OPSD-V, an on-policy self-distillation paradigm for post-training few-step autoregressive (AR) video diffusion models. Existing few-step AR video generators can produce long videos with low latency, but still suffer from error accumulation and weakened motion dynamics during long autoregressive rollout. OPSD-V reduces long-horizon degradation while preserving the original few-step infer

- **OpenCoF: Learning to Reason Through Video Generation** _(transformer financial time series)_
  [2026-07-09](https://arxiv.org/abs/2607.08763v1)
  Reasoning has become a core capability for large models, especially when reliable decisions require understanding logical consequences. Recent video generation models offer a reasoning path distinct from previous Chain-of-Thought (CoT): reasoning can unfold through temporally connected frames, known as Chain-of-Frame (CoF) reasoning. However, existing video generators are primarily trained on gene

- **Wat3R: Underwater 3D Geometry Learning without Annotations** _(reinforcement learning portfolio)_
  [2026-07-09](https://arxiv.org/abs/2607.08772v1)
  Estimating 3D geometry in underwater environments presents unique challenges due to light attenuation, scattering, and the absence of large-scale, high-quality 3D annotations. Pioneering methods rely on massive dense annotations that are impractical in underwater settings. In this paper, we propose Wat3R, a cross-domain semi-supervised learning framework designed to adapt feed-forward 3D reconstru

- **Enhancing In-context Panoramic Generation via Geometric-aware Pretraining** _(reinforcement learning portfolio)_
  [2026-07-09](https://arxiv.org/abs/2607.08765v1)
  In this work, we present Canvas360, a two-stage framework for in-context panoramic generation that combines geometry-aware pretraining with downstream task-specific fine-tuning. To address the lack of large-scale, high-quality training data tailored to in-context panoramic tasks, we propose Canvas360Dataset, a collection of 1M high-quality paired panoramic samples for style transfer, inpainting, o

- **OpenCoF: Learning to Reason Through Video Generation** _(reinforcement learning portfolio)_
  [2026-07-09](https://arxiv.org/abs/2607.08763v1)
  Reasoning has become a core capability for large models, especially when reliable decisions require understanding logical consequences. Recent video generation models offer a reasoning path distinct from previous Chain-of-Thought (CoT): reasoning can unfold through temporally connected frames, known as Chain-of-Frame (CoF) reasoning. However, existing video generators are primarily trained on gene

- **ZipDepth: Bringing Lightweight Zero-Shot Monocular Depth Anywhere, on Any Device** _(cryptocurrency trading)_
  [2026-07-09](https://arxiv.org/abs/2607.08771v1)
  Monocular depth estimation has seen remarkable progress through foundation models achieving robust zero-shot generalization, yet their computational demands place them far beyond the reach of embedded and mobile platforms. Lightweight alternatives exist, but have been developed almost exclusively within single-domain, self-supervised paradigms, failing silently under domain shift. We present ZipDe

- **Approaching Carnot Efficiency at Finite Power in an Experimentally Feasible Quantum Heat Engine** _(cryptocurrency trading)_
  [2026-07-09](https://arxiv.org/abs/2607.08713v1)
  Whether a heat engine can approach Carnot efficiency while maintaining finite power is a fundamental question in finite-time thermodynamics. For classical Markovian heat engines with local interactions, the power-efficiency trade-off forbids an asymptotic approach to Carnot efficiency at finite power. In quantum systems, by contrast, degeneracy, symmetry, and collective jumps have been theoretical

- **Quantifying randomness with measurement incompatibility** _(cryptocurrency trading)_
  [2026-07-09](https://arxiv.org/abs/2607.08697v1)
  We present a trade-off between the amount of observed measurement incompatibility and the capabilities of a classical Eavesdropper in a prepare-and-measure scenario. The result is based on a qualitative connection between measurement incompatibility and randomness generation together with the utilization of incompatibility witnesses as randomness certificates. This allows one to use a geometric me

- **Debris Disc Substructures Induced by Secular Planetary Perturbations** _(options volatility surface)_
  [2026-07-09](https://arxiv.org/abs/2607.08750v1)
  Observations of debris discs have the potential to provide us with valuable information about massive planets perturbing them gravitationally. In this work, we explore the evolution of the azimuthally-averaged (or axisymmetric) surface density (ASD) -- a characteristic routinely derived from observations -- in a disc secularly perturbed by an inner planet. We develop detailed analytical understand

- **AUTOPILOT VQA: Benchmarking Vision-Language Models for Incident-Centric Dashcam Understanding** _(options volatility surface)_
  [2026-07-09](https://arxiv.org/abs/2607.08745v1)
  Recent advances in Vision-Language Models, Large Language Models, and Multimodal Large Language Models have improved autonomous driving tasks such as scene understanding, decision making, trajectory prediction, and visual question answering. However, evaluating whether these models can reliably reason about safety-critical incidents remains challenging. To address this gap, we present AUTOPILOT-VQ

- **Validity of LLMs as data annotators: AMALIA on authority** _(options volatility surface)_
  [2026-07-09](https://arxiv.org/abs/2607.08731v1)
  A national language model offers a linguistic community its own instrument for measuring what its citizens say and value. Portugal's AMALIA, a publicly funded 9B-parameter model for European Portuguese, appears competitive on agreement alone: asked to code the moral foundation of authority, it agrees with trained human coders to within six F1 points of open models eight to thirteen times its size.

- **SLORR: Simple and Efficient In-Training Low-Rank Regularization** _(factor investing alpha)_
  [2026-07-09](https://arxiv.org/abs/2607.08754v1)
  Low-rank factorization is widely used to compress neural networks, but modern models are often not naturally amenable to aggressive factorization without significant accuracy loss. Existing training-time low-rank regularizers can improve compressibility, but they often require SVDs of large weight matrices, modify the model architecture (introducing additional trainable parameters), or rely on sta

- **Internal pseudospin, lepton-number superselection, and neutrino--antineutrino coherence in massive neutral-fermion one-particle states** _(factor investing alpha)_
  [2026-07-09](https://arxiv.org/abs/2607.08739v1)
  At fixed three-momentum, massive Dirac neutrino one-particle states span a 4D space of particle--antiparticle identity and helicity. We show that helicity flip, charge conjugation, and their product close an internal $SU(2)$ pseudospin subalgebra within $SU(4)$, distinct from the Wigner little group. Its helicity generator is the lepton-number-weighted spin rotation $U_1=2LJ_2$. The lepton-number 

- **The mini-Page Curve in Cosmology** _(factor investing alpha)_
  [2026-07-09](https://arxiv.org/abs/2607.08737v1)
  The black hole information paradox has motivated extensive study of how and when information escapes from evaporating black holes. Here we address the analogous question for cosmological horizons: when does an individual Hawking pair begin to carry information out of a de Sitter horizon? We study this problem in a class of two-dimensional flow geometries that interpolate smoothly between an asympt

## 3. GitHub Repos (Recently Updated)
- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-11)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[cikafeee/algorithmic-trading-backtest](https://github.com/cikafeee/algorithmic-trading-backtest)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-11)_
  📊 Analyze and validate trading strategies with a high-performance backtesting engine using PySpark, processing thousands of backtests on real market data.

- **[11Bhavin/Quant_Trading_Portfolio-](https://github.com/11Bhavin/Quant_Trading_Portfolio-)** ⭐ 0 · None _(updated 2026-07-11)_
  📈 Build and backtest automated trading strategies using Python to enhance your quantitative finance skills and explore the financial markets.

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 1 · Python _(updated 2026-07-11)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Mdsadikanwar/AlertPro-V2](https://github.com/Mdsadikanwar/AlertPro-V2)** ⭐ 0 · JavaScript _(updated 2026-07-11)_
  Multi-Mode Trading Bot with Crypto, Stock, Forex, Commodity + Backtest

- **[ssproduction13-ship-it/crypto-signal-bot](https://github.com/ssproduction13-ship-it/crypto-signal-bot)** ⭐ 0 · TypeScript _(updated 2026-07-11)_
  Telegram bot for crypto trading signals with AI analysis (Gemini), backtesting, paper trading

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-11)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[ashikscreativemath-commits/Paldo-ALM](https://github.com/ashikscreativemath-commits/Paldo-ALM)** ⭐ 17 · Python _(updated 2026-07-11)_
  🧠 Build adaptive algorithmic trading bots using machine learning and custom logic for MetaTrader 5 scalping and swing strategies.

- **[Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic)** ⭐ 2 · Python _(updated 2026-07-11)_
  This repository features Juno, an automated trade bot for Binance, designed for margin trading of cryptocurrencies. It utilizes advanced algorithmic strategies to optimize trading decisions and enhanc

- **[knoomdevbot/alpha-research](https://github.com/knoomdevbot/alpha-research)** ⭐ 0 · Python _(updated 2026-07-11)_
  Primary AOI alpha research repository for qfa-compatible models, factors, tests, and reports

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-07-11)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-07-11)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[rohailasim123/stat-arb-pairs-trading](https://github.com/rohailasim123/stat-arb-pairs-trading)** ⭐ 0 · Python _(updated 2026-07-11)_
  A statistical arbitrage research pipeline

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-07-11)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[Gzeu/quantluna](https://github.com/Gzeu/quantluna)** ⭐ 0 · Python _(updated 2026-07-10)_
  QuantLuna — Adaptive Kalman Filter pairs trading engine for crypto markets (spot + perpetual futures). Statistical arbitrage, cointegration testing, market-neutral strategies.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-11)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[FrizkyTrixter/Options-Trading-AI-Strategy](https://github.com/FrizkyTrixter/Options-Trading-AI-Strategy)** ⭐ 0 · Python _(updated 2026-07-10)_
  A Python framework for backtesting machine learning–driven call option strategies against buy-and-hold using rolling out-of-sample validation, Black–Scholes pricing, and strict lookahead-bias preventi

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-07-08)_
  A stock/futures auto trading framework using Shioaji API

## 4. Perplexity Strategy Synthesis
Based on the search results provided, **there are no specific, newly discovered systematic trading strategies with concrete parameters (time horizon, entry/exit rules, position sizing) for April 2026** that address your four specific requests: (1) crypto momentum with regime filters, (2) equity pair trading, (3) cheap options tail hedges, or (4) edges from recent academic papers or trading Twitter.

The available sources (general trading guides from Goat Funded Trader, Hantec Markets, and VT Markets) offer **generic, timeless frameworks** (e.g., "Pullback Trend with Fair Value Gaps," "SLC System," "CEST Framework") that are not tied to the specific market regime of April 2026 and lack the quantitative specificity you requested [1][2][5]. Consequently, I cannot flag strategies that have "degraded" in the last 6 months based on these sources, as they do not contain performance data for that specific period.

Below is an analysis of what the search results *do* provide for small accounts, followed by the necessary limitations and how to proceed given the data gap.

### What the Search Results Confirm for Small Accounts ($100–$1,000)
The sources agree that for retail traders with small capital, the most **actionable** approaches are generally **high-probability, short-term setups** rather than complex systematic strategies, due to transaction costs and leverage constraints.

| Strategy Type | Concrete Parameters (from General Sources) | Suitability for Small Accounts |
| :--- | :--- | :--- |
| **Pullback Trend with FVG** | **Time Horizon:** Intraday (5–15 min charts) [2]<br>**Entry:** Pullback to Fair Value Gap (FVG) after a trend move [2]<br>**Exit:** 1:3 Risk-to-Reward ratio [2]<br>**Sizing:** 1–2% risk per trade [3] | **High:** Avoids chasing price; defined risk [2] |
| **SLC System** | **Time Horizon:** Intraday (5-min entry, higher TF structure) [5]<br>**Entry:** Retest of Supply/Demand levels with confirmation [5]<br>**Exit:** Measured moves or next structure level [1]<br>**Sizing:** Tight stops beyond pattern extreme [1] | **High:** Focuses on "high probability levels" [5] |
| **Momentum/Breakout** | **Time Horizon:** Intraday (15-min to daily) [1]<br>**Entry:** Volume 2x+ normal average + decisive resistance break [3]<br>**Exit:** Scale out at predefined targets; exit before close [1]<br>**Sizing:** 1–2% account risk [3] | **Moderate:** Requires liquid assets; high volatility risk [3] |
| **Range Trading** | **Time Horizon:** Daily/Intraday [1]<br>**Entry:** Buy near support, sell near resistance [3]<br>**Exit:** Target 1.5–2x risk [3]<br>**Sizing:** 1–3 securities only [3] | **High:** Low stress; teaches price action [3] |

### Critical Limitations & Missing Data for Your Specific Requests
The search results fail to address the specific nuances of your query for the following reasons:

1.  **Crypto Momentum with Regime Filters:** No source provides a "regime filter" (e.g., using volatility regimes, funding rates, or macro indicators) for crypto momentum in 2026. The general advice is simply to "enter on pullbacks in the direction of momentum" using MACD or RSI [1].
2.  **Equity Pair Trading:** No source details a specific pair trading strategy (e.g., Long X / Short Y) with concrete correlation thresholds or entry rules for 2026.
3.  **Options Tail Hedges:** There is no mention of "cheap" tail hedges or specific options strategies (e.g., specific OTM put spreads) that are currently undervalued. General advice warns against "news-based trading" for new traders due to speed [3].
4.  **New Edges from Papers

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-07-11 via Conway's auto-publisher.*
