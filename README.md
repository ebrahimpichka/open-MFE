# open-MFE
### Open-Source Master of Financial Engineering Curriculum

A community-curated vault of openly available resources that replicates the rigorous syllabus of top MFE / Quant Finance programs — **Berkeley Haas, CMU MSCF, UChicago FinMath, Baruch MFE, and Columbia MFE**.

> **Philosophy:** Most of the time, every topic taught in a major MFE program has a freely available equivalent on the internet (or in the form of textbooks, lecture notes, etc.). This repository maps the full curriculum and points you to the best open resources for each subject.

---

## Table of Contents

1. [Repository Structure](#repository-structure)
2. [Curriculum Overview](#curriculum-overview)
3. [Module 0 — Pre-Program Foundations](#module-0--pre-program-foundations)
4. [Module 1 — Mathematical Foundations](#module-1--mathematical-foundations)
5. [Module 2 — Derivatives & Options](#module-2--derivatives--options)
6. [Module 3 — Fixed Income & Credit](#module-3--fixed-income--credit)
7. [Module 4 — Quantitative Methods & Econometrics](#module-4--quantitative-methods--econometrics)
8. [Module 5 — Financial Programming](#module-5--financial-programming)
9. [Module 6 — Machine Learning & Data Science](#module-6--machine-learning--data-science)
10. [Module 7 — Risk Management](#module-7--risk-management)
11. [Module 8 — Portfolio Management & Investments](#module-8--portfolio-management--investments)
12. [Module 9 — Trading & Market Microstructure](#module-9--trading--market-microstructure)
13. [Module 10 — Specialized Topics](#module-10--specialized-topics)
14. [Module 11 — Capstone & Applied Projects](#module-11--capstone--applied-projects)
15. [Study Paths](#study-paths)
16. [Contributing](#contributing)

---

## Repository Structure

```
open-MFE/
│
├── README.md
│
├── 00_pre_program/
│   ├── calculus/
│   ├── linear_algebra/
│   ├── probability_statistics/
│   └── programming_intro/
│
├── 01_mathematical_foundations/
│   ├── stochastic_calculus/
│   └── pdes_for_finance/
│
├── 02_derivatives_options/
│   ├── options_pricing/
│   ├── numerical_methods/
│   └── futures_swaps_exotics/
│
├── 03_fixed_income_credit/
│   ├── fixed_income_markets/
│   ├── term_structure_models/
│   ├── fixed_income_derivatives/
│   └── credit_risk/
│
├── 04_quant_methods_econometrics/
│   ├── empirical_methods_and_statistics/
│   └── financial_time_series/
│
├── 05_financial_programming/
│   ├── python_for_finance/
│   ├── cpp_for_finance/
│   ├── sql_and_databases/
│   └── high_performance_computing/
│
├── 06_machine_learning_data_science/
│   ├── ml_fundamentals/
│   ├── ml_for_finance/               
│   ├── deep_learning/
│   ├── nlp_for_finance/
│   ├── reinforcement_learning/
│   └── alternative_and_hf_data/
│
├── 07_risk_management/
│   └── RESOURCES.md                    
│
├── 08_portfolio_investments/
│   ├── asset_pricing_and_portfolio_theory/
│   ├── quantitative_asset_management/
│   └── financial_optimization/
│
├── 09_trading_microstructure/
│   ├── market_microstructure/
│   ├── algorithmic_execution/
│   └── quantitative_strategies/
│
├── 10_specialized_topics/
│   ├── macro_finance/
│   ├── foreign_exchange/
│   ├── blockchain_cryptoassets/
│   └── generative_ai_for_finance/
│
└── 11_capstone_projects/
    ├── project_ideas/
    ├── datasets/
    └── past_projects/
```

---

## Curriculum Overview

| Module | Topics | Difficulty |
|--------|---------|------------|
| [0 — Pre-Program](#module-0--pre-program-foundations) | Calculus, LinAlg, Prob/Stats, Python | ⭐⭐ |
| [1 — Mathematical Foundations](#module-1--mathematical-foundations) | Stochastic Calculus, Itô, PDEs | ⭐⭐⭐⭐⭐ |
| [2 — Derivatives & Options](#module-2--derivatives--options) | Black-Scholes, Advanced Models, Numerical Methods | ⭐⭐⭐⭐ |
| [3 — Fixed Income & Credit](#module-3--fixed-income--credit) | Bond Math, Term Structure, Credit Risk | ⭐⭐⭐⭐ |
| [4 — Quant Methods](#module-4--quantitative-methods--econometrics) | Econometrics, Time Series, GARCH | ⭐⭐⭐ |
| [5 — Financial Programming](#module-5--financial-programming) | Python, C++, SQL, HPC | ⭐⭐⭐ |
| [6 — ML & Data Science](#module-6--machine-learning--data-science) | ML, ML for Finance, Deep Learning, NLP, RL | ⭐⭐⭐⭐ |
| [7 — Risk Management](#module-7--risk-management) | VaR, Credit Risk, XVA, Regulation | ⭐⭐⭐⭐ |
| [8 — Portfolio & Investments](#module-8--portfolio-management--investments) | MPT, CAPM, Factor Models, Optimization | ⭐⭐⭐ |
| [9 — Trading & Microstructure](#module-9--trading--market-microstructure) | Algo Trading, HFT, Quant Strategies | ⭐⭐⭐⭐ |
| [10 — Specialized Topics](#module-10--specialized-topics) | Blockchain, FX, Macro, GenAI | ⭐⭐⭐ |
| [11 — Capstone](#module-11--capstone--applied-projects) | Applied Projects, Research | ⭐⭐⭐⭐⭐ |

---

## [Module 0 — Pre-Program Foundations](./00_pre_program/)

Prerequisites expected before starting the core curriculum. Start here if you have gaps.

### [0.1 Calculus & Real Analysis](./00_pre_program/calculus/)
Topics: Differential and integral calculus, multivariable calculus, Taylor series, Lagrange multipliers, real analysis basics (sequences, limits, continuity).

### [0.2 Linear Algebra](./00_pre_program/linear_algebra/)
Topics: Matrix operations, eigenvalues/eigenvectors, SVD, PCA, Gram-Schmidt, positive definite matrices, optimization with linear constraints.

### [0.3 Probability & Statistics](./00_pre_program/probability_statistics/)
Topics: Probability spaces, random variables, distributions (Normal, Log-Normal, Poisson, Binomial), MLE, hypothesis testing, confidence intervals, LLN, CLT.

### [0.4 Introduction to Programming](./00_pre_program/programming_intro/)
Topics: Python basics (variables, loops, functions, OOP), NumPy, Pandas, Matplotlib, basic data structures.

---

## [Module 1 — Mathematical Foundations](./01_mathematical_foundations/)

The mathematical backbone of quantitative finance. Everything else builds on this module.

### [1.1 Stochastic Calculus](./01_mathematical_foundations/stochastic_calculus/)
Topics: Filtrations and sigma-algebras, conditional expectation, martingales, Brownian motion, Markov processes, stopping times. Itô integral construction, Itô's Lemma, SDEs (GBM, OU process), quadratic variation. Change of measure, Girsanov's theorem, risk-neutral measure, FTAP, Feynman-Kac formula.

Based on: `Berkeley: MFE 230Q | CMU: 46944, 46945 | UChicago: FINM 34000, FINM 34500 | Baruch: MTH 9831, MTH 9832`

### [1.2 PDEs for Finance](./01_mathematical_foundations/pdes_for_finance/)
Topics: Parabolic PDEs, heat equation, Black-Scholes PDE derivation and solution, boundary conditions, free-boundary problems (American options), connection to stochastic calculus via Feynman-Kac.

Based on: `Berkeley: MFE 230D | CMU: 46932 | Baruch: MTH 9833`

---

## [Module 2 — Derivatives & Options](./02_derivatives_options/)

### [2.1 Options Pricing](./02_derivatives_options/options_pricing/)
Topics: No-arbitrage pricing, CRR binomial model, Black-Scholes model and formula, put-call parity, Greeks, delta-hedging, implied volatility, volatility smile/surface. Local volatility (Dupire), stochastic volatility (Heston, SABR), jump-diffusion models (Merton, Kou), variance swaps, model calibration.

Based on: `Berkeley: MFE 230A, MFE 230D | CMU: 46973, 46915 | UChicago: FINM 33000, FINM 34500 | Baruch: MTH 9852, MTH 9853`

### [2.2 Numerical Methods](./02_derivatives_options/numerical_methods/)
Topics: Monte Carlo simulation (variance reduction: antithetics, control variates, importance sampling), finite difference methods (explicit, implicit, Crank-Nicolson), binomial/trinomial trees, Fourier/FFT pricing methods.

Based on: `Berkeley: MFE 230D | CMU: 46932 | UChicago: FINM 32000 | Baruch: MTH 9821`

### [2.3 Futures, Swaps & Exotic Options](./02_derivatives_options/futures_swaps_exotics/)
Topics: Futures and forward pricing, interest rate swaps, CDS basics, barrier options, Asian options, lookback options, digital options, structured products.

Based on: `CMU: 46974 | UChicago: FINM 37000 | Berkeley: MFE 230D`

---

## [Module 3 — Fixed Income & Credit](./03_fixed_income_credit/)

### [3.1 Fixed Income Markets & Bond Mathematics](./03_fixed_income_credit/fixed_income_markets/)
Topics: Bond pricing and yield, duration and convexity, DV01, yield curve construction (bootstrapping), term structure theories, mortgage-backed securities (MBS).

Based on: `Berkeley: MFE 230I | CMU: 46956 | UChicago: FINM 37400 | Baruch: MTH 9855`

### [3.2 Term Structure Models](./03_fixed_income_credit/term_structure_models/)
Topics: Short-rate models (Vasicek, CIR, Hull-White), affine term structure models, Heath-Jarrow-Morton (HJM) framework, LIBOR Market Model (LMM/BGM), forward rate agreements.

Based on: `Berkeley: MFE 230I | CMU: 46956 | UChicago: FINM 37500`

### [3.3 Fixed Income Derivatives](./03_fixed_income_credit/fixed_income_derivatives/)
Topics: Caps, floors, swaptions, callable bonds, bond futures, convexity adjustments, pricing under HJM and LMM.

Based on: `UChicago: FINM 37500 | Berkeley: MFE 230I | Baruch: MTH 9855`

### [3.4 Credit Risk & Credit Markets](./03_fixed_income_credit/credit_risk/)
Topics: Structural models (Merton), reduced-form/intensity models (Jarrow-Turnbull, Duffie-Singleton), CDS pricing and credit curves, CDOs and securitization, CVA, DVA, XVA.

Based on: `UChicago: FINM 35700 | Berkeley: MFE 230H | Baruch: MTH 9856`

---

## [Module 4 — Quantitative Methods & Econometrics](./04_quant_methods_econometrics/)

### [4.1 Empirical Methods & Multivariate Statistics](./04_quant_methods_econometrics/empirical_methods_and_statistics/)
Topics: MLE, GMM, OLS/GLS, panel data, event studies, factor model estimation, EMH. Covariance matrix estimation (shrinkage, Ledoit-Wolf), PCA, copula models, extreme value theory (EVT).

Based on: `Berkeley: MFE 230E | CMU: 46921, 46923 | UChicago: FINM 34700`

### [4.2 Financial Time Series](./04_quant_methods_econometrics/financial_time_series/)
Topics: AR, MA, ARMA, ARIMA models, ARCH/GARCH family (EGARCH, GJR-GARCH), cointegration, VAR models, volatility forecasting, realized volatility, Kalman filter.

Based on: `CMU: 46929 | Berkeley: MFE 230E | Baruch: MTH 9875`

---

## [Module 5 — Financial Programming](./05_financial_programming/)

### [5.1 Python for Quantitative Finance](./05_financial_programming/python_for_finance/)
Topics: NumPy, Pandas, SciPy, Matplotlib/Plotly, financial APIs, OOP for pricing libraries, performance profiling.

Based on: `CMU: 46901, 46903 | UChicago: FINM 32400, FINM 32500 | Berkeley: MFE 230P`

### [5.2 C++ for Quantitative Finance](./05_financial_programming/cpp_for_finance/)
Topics: C++ fundamentals (types, pointers, memory management), STL, templates, OOP for pricing libraries, Monte Carlo engines in C++, QuantLib.

Based on: `CMU: 46902 | UChicago: FINM 32600 | Baruch: MTH 9821`

### [5.3 SQL & Databases](./05_financial_programming/sql_and_databases/)
Topics: SQL for financial data (aggregation, joins, window functions), NoSQL, REST APIs, data pipelines, backtesting framework architecture.

Based on: `CMU: 46912 | UChicago: FINM 32900`

### [5.4 High-Performance Computing](./05_financial_programming/high_performance_computing/)
Topics: Parallel computing (OpenMP, MPI), GPU computing (CUDA for Monte Carlo), vectorized numerical methods, memory optimization, profiling.

Based on: `UChicago: FINM 32950, FINM 32700`

---

## [Module 6 — Machine Learning & Data Science](./06_machine_learning_data_science/)

### [6.1 Machine Learning Fundamentals](./06_machine_learning_data_science/ml_fundamentals/)
Topics: Supervised learning (regression, classification, regularization), decision trees, random forests, gradient boosting, unsupervised learning, cross-validation, bias-variance tradeoff.

Based on: `CMU: 46926 | UChicago: FINM 33160 | Berkeley: MFE 230P`

### [6.2 ML for Finance](./06_machine_learning_data_science/ml_for_finance/)
Topics: Financial data structures and feature engineering, factor-based ML models, backtesting with ML signals, meta-labeling, tick data features, alpha research pipeline.

Based on: `CMU: 46926, 46927 | UChicago: FINM 33160`

### [6.3 Deep Learning](./06_machine_learning_data_science/deep_learning/)
Topics: MLPs, CNNs, RNNs/LSTMs, attention and Transformers, autoencoders, training techniques, option pricing with neural networks, trading signal generation.

Based on: `CMU: 46937 | UChicago: FINM 33165`

### [6.4 NLP for Finance](./06_machine_learning_data_science/nlp_for_finance/)
Topics: Text preprocessing, word embeddings, topic models, sentiment analysis for trading, LLMs for finance, earnings call analysis.

Based on: `CMU: 46924 | UChicago: FINM 33200`

### [6.5 Reinforcement Learning](./06_machine_learning_data_science/reinforcement_learning/)
Topics: MDPs, Q-learning, Deep Q-Networks (DQN), policy gradient methods (PPO, A3C), RL for optimal execution and portfolio management.

Based on: `UChicago: FINM 33165`

### [6.6 Alternative & High-Frequency Data](./06_machine_learning_data_science/alternative_and_hf_data/)
Topics: Alternative data sources (satellite, credit card, web scraping), tick data processing, order book data, TAQ data, realized volatility, microstructure noise.

Based on: `UChicago: FINM 34600 | CMU: 46923`

---

## [Module 7 — Risk Management](./07_risk_management/)

Topics: VaR — parametric, historical simulation, Monte Carlo; Expected Shortfall (ES/CVaR); stress testing; Greeks-based P&L risk; Basel III/FRTB. PD/LGD/EAD, IRB approach, credit VaR, CreditMetrics, KMV. Funding and market liquidity risk, CVA/DVA/FVA/XVA, OTC derivatives and CCPs, systemic risk.

Based on: `Berkeley: MFE 230H | CMU: 46954 | UChicago: FINM 36700 | Baruch: MTH 9876`

---

## [Module 8 — Portfolio Management & Investments](./08_portfolio_investments/)

### [8.1 Asset Pricing & Portfolio Theory](./08_portfolio_investments/asset_pricing_and_portfolio_theory/)
Topics: DCF, no-arbitrage pricing, mean-variance optimization (Markowitz), efficient frontier, Sharpe ratio, CAPM, multi-factor models (APT, Fama-French, Carhart), SDF framework, performance attribution.

Based on: `Berkeley: MFE 230A | CMU: 46972 | UChicago: FINM 36700 | Baruch: MTH 9876`

### [8.2 Quantitative Asset Management](./08_portfolio_investments/quantitative_asset_management/)
Topics: Factor investing (value, momentum, quality, low-vol), smart beta, portfolio construction with constraints, transaction cost modeling, alpha decay, Black-Litterman.

Based on: `CMU: 46979 | UChicago: FINM 36700`

### [8.3 Financial Optimization](./08_portfolio_investments/financial_optimization/)
Topics: LP/QP, convex optimization, semidefinite programming (SDP), robust optimization, stochastic control.

Based on: `CMU: 46976 | UChicago: FINM 34800`

---

## [Module 9 — Trading & Market Microstructure](./09_trading_microstructure/)

### [9.1 Market Microstructure](./09_trading_microstructure/market_microstructure/)
Topics: Limit order book (LOB) dynamics, bid-ask spread decomposition (Roll, Kyle, Glosten-Milgrom), price impact models, information asymmetry, market fragmentation.

Based on: `CMU: 46982 | UChicago: FINM 37601`

### [9.2 Algorithmic & Optimal Execution](./09_trading_microstructure/algorithmic_execution/)
Topics: TWAP, VWAP, implementation shortfall, Almgren-Chriss optimal execution, dark pools, co-location, TCA, market-making (Avellaneda-Stoikov).

Based on: `CMU: 46982 | UChicago: FINM 37601, FINM 34600`

### [9.3 Quantitative Trading Strategies](./09_trading_microstructure/quantitative_strategies/)
Topics: Statistical arbitrage, pairs trading, mean-reversion, momentum, cross-sectional equity strategies, signal construction and decay, backtesting methodology.

Based on: `UChicago: FINM 33150, FINM 35910`

---

## [Module 10 — Specialized Topics](./10_specialized_topics/)

### [10.1 Macro Finance](./10_specialized_topics/macro_finance/)
Topics: Consumption-based asset pricing, recursive utility (Epstein-Zin), long-run risk, rare disasters, bond-equity relationship, central bank policy and markets.

Based on: `CMU: 46975 | UChicago: FINM 35900, FINM 35000`

### [10.2 Foreign Exchange](./10_specialized_topics/foreign_exchange/)
Topics: FX spot/forward markets, CIP/UIP, FX options (Garman-Kohlhagen), FX volatility surface, carry trade, EM currencies.

Based on: `UChicago: FINM 37301`

### [10.3 Blockchain & Cryptoassets](./10_specialized_topics/blockchain_cryptoassets/)
Topics: Blockchain fundamentals, smart contracts, DeFi (DEXs, AMMs), tokenomics, crypto derivatives, regulatory landscape.

Based on: `CMU: 46912 | UChicago: FINM 31200`

### [10.4 Generative & Agentic AI for Finance](./10_specialized_topics/generative_ai_for_finance/)
Topics: LLMs in financial research and trading, RAG for financial data, autonomous AI agents, LLM-based backtesting, AI regulation.

Based on: `UChicago: FINM 33200`

---

## [Module 11 — Capstone & Applied Projects](./11_capstone_projects/)

### [11.1 Project Ideas](./11_capstone_projects/project_ideas/)
Curated prompts that simulate real quant roles: volatility surface construction, short-rate model calibration, VaR engine build, factor paper replication, statistical arbitrage strategy, optimal execution simulator.

### [11.2 Open Datasets](./11_capstone_projects/datasets/)
Curated list of free data sources: equity (Yahoo Finance, CRSP), options (OptionMetrics, CBOE), fixed income (FRED), alternative data (Quandl, Kaggle), order book and TAQ data.

### [11.3 Past Project Examples](./11_capstone_projects/past_projects/)
Links to publicly available MFE capstone reports and associated code repositories.

---

## Study Paths

**Derivatives / Options Quant**
`0 → 1 → 2 → 3 → 5.1 → 5.2 → 7 → 11`

**Quant Researcher / ML**
`0 → 1 → 4 → 5.1 → 6.1 → 6.2 → 6.3 → 8 → 9.3 → 11`

**Risk Management**
`0 → 1 → 2 → 3 → 4 → 7 → 8 → 11`

**Systematic / Algo Trading**
`0 → 1 → 5 → 6.1 → 6.2 → 9 → 4.2 → 6.6 → 11`

**Full Curriculum (18–24 months)**
`0 → 1 → 2 → 3 → 4 → 5 → 6 → 7 → 8 → 9 → 10 → 11`

---

## Contributing

Each sub-module contains a `RESOURCES.md` file ready for community contributions. Add resources using the template in [`CONTRIBUTING.md`](./CONTRIBUTING.md) and open a pull request.

**Resource types:** Textbooks · Online courses (MIT OCW, Coursera, YouTube) · Papers (arXiv, SSRN) · Code/Notebooks · Recorded lectures

---

*open-MFE is a community project not affiliated with UC Berkeley, Carnegie Mellon University, University of Chicago, Baruch College, or Columbia University. Curriculum structure synthesized from publicly available program information (2025–2026).*
