# Quant_finance_2025 – Mini Projects (Erdös)

This repository contains four mini projects completed as part of the **Quant Finance Boot Camp
Summer 2025** at the **Erdös Institute**. Each project explores a key concept in quantitative finance, from portfolio construction to option pricing and risk management.

---

## Contents

### [Mini Project 1: Portfolio Construction](./Mini%20Project%201.ipynb)
**Goal**: Construct two investment portfolios — one high-risk and one low-risk — using S&P 500 historical data.

- Downloaded and cleaned real stock data using `yfinance`.
- Quantitatively assessed risk using volatility and market cap.
- Justified portfolio classification with metrics and visualizations.

### [Mini Project 2: Testing Normality of Returns](./Mini%20Project%202.ipynb)
**Goal**: Investigate whether log returns of stocks/indexes follow a normal distribution.

- Applied D'Agostino-Pearson tests and rolling window analysis.
- Examined the effects of tail-trimming on return distributions.
- Evaluated normality at both individual stock and portfolio level.

### [Mini Project 3: Option Sensitivity Visualization](./Mini%20Project%203.ipynb)
**Goal**: Visualize how Black-Scholes call and put option prices respond to time and spot price.

- Implemented Black-Scholes pricing model for European options.
- Plotted option price sensitivity to expiration and spot price.
- Reflected on how Greeks like delta and theta influence pricing.

### [Mini Project 4: Delta Hedging under Volatility Shifts](./Mini%20Project%204.ipynb)
**Goal**: Analyze how non-constant volatility impacts delta hedging for sold call options.

- Simulated stock paths with randomized volatility per time step.
- Implemented a delta hedging strategy and visualized profit distributions.
- Interpreted the impact of volatility on hedging effectiveness.

---

## Tools & Libraries

- Python 3
- NumPy, Pandas
- Matplotlib, Seaborn
- SciPy
- yFinance
