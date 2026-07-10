# Trading Nightly Research Brief — 2026-07-10

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-07-10T03:33:34, run time 29.2s._

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
- **[HaSerZin/trade_political_distance_wto](https://github.com/HaSerZin/trade_political_distance_wto)** ⭐ 3 · Jupyter Notebook _(updated 2026-07-10)_
  🌍 Model political distance and trade dynamics using a quantitative framework to enhance understanding of international trade relationships.

- **[yanxinnnnnn/El-Psy-Quant](https://github.com/yanxinnnnnn/El-Psy-Quant)** ⭐ 0 · Python _(updated 2026-07-10)_
  An AI-native quantitative research and trading platform built in public.

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-07-10)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[scanner72/no-code-signal-bot](https://github.com/scanner72/no-code-signal-bot)** ⭐ 1 · TypeScript _(updated 2026-07-10)_
  Visual no-code builder for crypto trading strategies, backtesting & automated bots

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 1 · Svelte _(updated 2026-07-10)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[ssproduction13-ship-it/crypto-signal-bot](https://github.com/ssproduction13-ship-it/crypto-signal-bot)** ⭐ 0 · TypeScript _(updated 2026-07-10)_
  Telegram bot for crypto trading signals with AI analysis (Gemini), backtesting, paper trading

- **[astarek1983/street-algo-trader](https://github.com/astarek1983/street-algo-trader)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-10)_
  🚀 Implement algorithmic trading strategies for a Jane Street-style exchange, featuring market-making, arbitrage, and momentum signals.

- **[Anna-007-tech/algorithmic-trading-ai](https://github.com/Anna-007-tech/algorithmic-trading-ai)** ⭐ 2 · None _(updated 2026-07-10)_
  📈 Explore AI-driven trading strategies through data analysis of forex and crypto volatility using PCA, K-means, and neural networks.

- **[arnolddelaguila/Advanced-Multi-Asset-Algorithmic-Trading-System-with-Machine-Learning-Integration](https://github.com/arnolddelaguila/Advanced-Multi-Asset-Algorithmic-Trading-System-with-Machine-Learning-Integration)** ⭐ 2 · Jupyter Notebook _(updated 2026-07-10)_
  Explore an advanced multi-asset algorithmic trading system with machine learning integration. Optimize strategies, backtest rigorously, and achieve high performance. 🐙📈

- **[knoomdevbot/alpha-research](https://github.com/knoomdevbot/alpha-research)** ⭐ 0 · Python _(updated 2026-07-10)_
  Primary AOI alpha research repository for qfa-compatible models, factors, tests, and reports

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-07-10)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-07-10)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-07-10)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[Gzeu/quantluna](https://github.com/Gzeu/quantluna)** ⭐ 0 · Python _(updated 2026-07-09)_
  QuantLuna — Adaptive Kalman Filter pairs trading engine for crypto markets (spot + perpetual futures). Statistical arbitrage, cointegration testing, market-neutral strategies.

- **[El-Moatasem/robust-pairs-trading-synthetic-regimes](https://github.com/El-Moatasem/robust-pairs-trading-synthetic-regimes)** ⭐ 0 · Python _(updated 2026-07-09)_
  MScFE 690 capstone research codebase for ML-enhanced equity pairs trading, synthetic market-regime robustness testing, cointegration-based statistical arbitrage, ML trade filtering, and risk-aware bac

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-10)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-07-08)_
  A stock/futures auto trading framework using Shioaji API

- **[milgar7969/alpaca-options-framework](https://github.com/milgar7969/alpaca-options-framework)** ⭐ 20 · Python _(updated 2026-07-06)_
  A Python framework for building live options trading bots on Alpaca Markets — asyncio, WebSocket streaming, position management, and all the API workarounds documented.

## 4. Perplexity Strategy Synthesis
For retail traders with small accounts ($100–$1000) in April 2026, the most **actionable** strategies are **pullback trend trading with Fair Value Gaps (FVG)** in crypto, **swing trend following** in equities, and **news-based volatility trading**; however, **pure momentum breakout strategies without regime filters** have significantly **DEGRADED** in the last 6 months due to overcrowding and fake-outs[1][2]. Direct "equity pair trading" and "cheap OTM options tail hedges" are largely **inaccessible** or **inefficient** for sub-$1000 accounts due to commission structures and liquidity constraints, making trend-following and volatility capture the most viable paths[3][4].

### 1. Crypto Momentum with Regime Filters (Pullback-to-FVG Strategy)
*   **Status:** **High Actionability** (Best for small accounts).
*   **Why:** Avoids chasing price; uses institutional Fair Value Gaps for precise entry[2].
*   **Time Horizon:** 5-minute to 15-minute charts (intraday swing); hold 1–4 hours[1][2].
*   **Regime Filter:** Trade only when price is above the **20 EMA** and **50 EMA** (bullish trend) or below both (bearish trend); ensure price is making **higher highs/lows**[1].
*   **Entry Rule:**
    1.  Identify a strong impulse move.
    2.  Wait for a pullback into a **Fair Value Gap (FVG)** formed by the impulse candle (the gap between the wick of the first and third candle in a 3-candle sequence)[2].
    3.  Enter on a **reversal candle** (e.g., bullish engulfing) closing inside the FVG[2].
*   **Exit Rule:**
    *   **Target:** 3:1 Risk-to-Reward (e.g., if risking $10, target $30)[2].
    *   **Stop:** Below the recent swing low or the FVG boundary[2].
    *   **Scale Out:** Take 50% profit at 1.5R, move stop to breakeven, hold rest for 3R[2].
*   **Position Sizing:** Risk **1–2%** of account per trade ($1–$20 on a $1000 account)[4].
*   **Source:** "Pullback Trend Strategy with FVG" (2026 Small Account Trading)[2].

### 2. Equity Signal Trading (Trend Following with Hull Moving Average)
*   **Status:** **High Actionability** (Swing Trading).
*   **Why:** Avoids the need for complex pair spreads; works well with low commissions on fractional shares[3][5].
*   **Time Horizon:** 4-hour to Daily charts; hold 2–10 days[3].
*   **Regime Filter:** Use the **Hull Moving Average (10/10 setting)**; only trade long if price is above the Hull and the Hull is rising; short if below and falling[5].
*   **Entry Rule:**
    1.  Confirm trend direction (higher highs/lows)[1].
    2.  Wait for a pullback to the **Hull Moving Average** or a **20 EMA** support[5].
    3.  Enter on a **bounce candle** (close above the Hull) with volume confirmation[5].
*   **Exit Rule:**
    *   **Target:** 2:1 Risk-to-Reward (e.g., $500 risk → $1,000 target)[4].
    *   **Stop:** Below the recent swing low or Hull line[5].
    *   **Trailing:** Move stop to breakeven after 1R profit; trail below the Hull MA[5].
*   **Position Sizing:** Risk **1%** per trade; adjust share size so stop distance equals 1% loss[5].
*   **Source:** "The E

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-07-10 via Conway's auto-publisher.*
