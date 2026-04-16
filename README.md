# Quant Developer, HFT & Systematic Trading — Learning Repository

A structured, hands-on curriculum with Jupyter notebooks covering everything needed to become a quantitative developer specializing in high-frequency and systematic trading.

## Prerequisites
- Python 3.10+
- Basic programming experience
- High school math (calculus, linear algebra refresher provided)

## Curriculum Overview

| # | Module | Notebooks | Status |
|---|--------|-----------|--------|
| 1 | [Mathematical & Statistical Foundations](01_math_foundations/) | 5 | 🔲 |
| 2 | [Financial Markets & Instruments](02_financial_markets/) | 5 | 🔲 |
| 3 | [Data Engineering & Infrastructure](03_data_engineering/) | 5 | 🔲 |
| 4 | [Alpha Research & Signal Generation](04_alpha_research/) | 5 | 🔲 |
| 5 | [Backtesting & Strategy Development](05_backtesting/) | 5 | 🔲 |
| 6 | [Execution & High-Frequency Trading](06_execution_hft/) | 5 | 🔲 |
| 7 | [Risk Management & Production](07_risk_production/) | 5 | 🔲 |

## Detailed Topic Map

### Module 1: Mathematical & Statistical Foundations
- `01_linear_algebra.ipynb` — Vectors, matrices, eigenvalues, PCA for finance
- `02_probability_statistics.ipynb` — Distributions, hypothesis testing, Bayesian inference
- `03_stochastic_calculus.ipynb` — Brownian motion, Itô's lemma, SDEs
- `04_time_series.ipynb` — Stationarity, autocorrelation, ARIMA, GARCH
- `05_optimization.ipynb` — Convex optimization, gradient descent, Lagrange multipliers

### Module 2: Financial Markets & Instruments
- `01_market_microstructure.ipynb` — Order books, bid-ask spread, market makers, tick data
- `02_equities_futures_options.ipynb` — Pricing, Greeks, payoff structures
- `03_fixed_income.ipynb` — Yield curves, duration, convexity
- `04_derivatives_pricing.ipynb` — Black-Scholes, binomial trees, Monte Carlo
- `05_risk_measures.ipynb` — VaR, CVaR, Sharpe, Sortino, max drawdown

### Module 3: Data Engineering & Infrastructure
- `01_market_data.ipynb` — Tick data, OHLCV, order book snapshots
- `02_data_cleaning.ipynb` — Outliers, missing data, corporate actions
- `03_database_design.ipynb` — Time-series DBs (Arctic, InfluxDB, TimescaleDB)
- `04_data_pipelines.ipynb` — Streaming vs batch, event-driven architectures
- `05_apis_data_sources.ipynb` — Exchange APIs, alternative data

### Module 4: Alpha Research & Signal Generation
- `01_factor_models.ipynb` — Fama-French, momentum, value, quality
- `02_statistical_arbitrage.ipynb` — Pairs trading, cointegration, mean reversion
- `03_ml_for_finance.ipynb` — Feature engineering, cross-validation pitfalls, overfitting
- `04_alternative_data.ipynb` — Sentiment, satellite, web scraping
- `05_signal_combination.ipynb` — Signal weighting, turnover analysis, alpha decay

### Module 5: Backtesting & Strategy Development
- `01_backtesting_frameworks.ipynb` — Event-driven vs vectorized backtesting
- `02_transaction_costs.ipynb` — Realistic simulation of costs & slippage
- `03_overfitting_bias.ipynb` — Walk-forward, combinatorial purged CV
- `04_portfolio_construction.ipynb` — Mean-variance, risk parity, Kelly criterion
- `05_performance_analysis.ipynb` — Metrics, attribution, regime analysis

### Module 6: Execution & High-Frequency Trading
- `01_execution_algos.ipynb` — TWAP, VWAP, implementation shortfall
- `02_latency_systems.ipynb` — Low-latency design, C++/Rust concepts, kernel bypass
- `03_market_making.ipynb` — Inventory management, adverse selection
- `04_hft_signals.ipynb` — Order flow imbalance, trade classification
- `05_colocation_network.ipynb` — Exchange connectivity, feed handlers

### Module 7: Risk Management & Production
- `01_position_sizing.ipynb` — Kelly criterion, fractional Kelly, margin
- `02_realtime_risk.ipynb` — PnL, exposure, Greeks dashboards
- `03_regulatory.ipynb` — MiFID II, Reg NMS, reporting requirements
- `04_production_deployment.ipynb` — Monitoring, alerting, failover
- `05_psychology_process.ipynb` — Systematic discipline, model governance

## Recommended Reading
- *Advances in Financial Machine Learning* — Marcos López de Prado
- *Algorithmic Trading* — Ernest Chan
- *Trading and Exchanges* — Larry Harris
- *Options, Futures, and Other Derivatives* — John Hull
- *Quantitative Trading* — Ernest Chan
- *Machine Learning for Asset Managers* — Marcos López de Prado
- *The Man Who Solved the Market* — Gregory Zuckerman

## Setup

1. **Create a virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On macOS/Linux
   ```

2. **Install dependencies**
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

3. **Launch JupyterLab**
   ```bash
   jupyter lab
   ```
   This will open JupyterLab in your browser at `http://localhost:8888`
