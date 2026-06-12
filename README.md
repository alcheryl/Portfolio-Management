# Portfolio-Management

## Overview

Our team acted as portfolio managers at a simulated asset management firm. The objective was to construct, manage, and evaluate two mutual funds benchmarked against the Dow Jones Industrial Average (DJIA):

* **Active Fund:** A Large-Cap Value portfolio designed to outperform the DJIA on a risk-adjusted basis.
* **Passive Fund:** A full-replication portfolio designed to closely track the DJIA while minimizing tracking error.

Both funds started with a notional capital of **USD 50 million** and were managed over the period from **May 2025 to May 2026**. The project covers portfolio construction, rebalancing decisions, futures-based exposure management, and performance evaluation.

## Repository Contents

### `Active_Fund_Calculation_Code.ipynb`
Python code for the **Active Fund**. This notebook covers:
- Portfolio construction of 14 large-cap value stocks across 7 sectors (Financials, Energy, Healthcare, Industrials, Consumer Staples, Utilities, Communication Services).
- Application of the **Black-Litterman model with Absolute Views** to optimize portfolio weights by maximizing the Sharpe ratio.
- Simulation of the portfolio rebalancing event on October 29, 2025.
- Calculation of performance metrics: annualized return, volatility, Sharpe ratio, Treynor ratio, Jensen's Alpha, Information ratio, and Maximum Drawdown.
- **Performance attribution** using the Brinson framework (allocation, selection, and interaction effects).
- Style exposure analysis (large-cap value classification).

### `Passive_Fund_Calculation_Code.ipynb`
Python code for the **Passive Fund**. This notebook covers:
- Portfolio construction via **full replication** of all 30 DJIA constituents, purchasing an equal number of shares per ticker in line with the index's price-weighted methodology.
- Calculation of the **hedge ratio** and number of E-Mini DJIA Futures contracts required to offset cash drag from the 5% cash reserve.
- Simulation of semi-annual rebalancing and dividend reinvestment.
- **Tracking error** monitoring relative to the DJIA benchmark.
- Calculation of key metrics: NAV, cumulative return, beta, Sharpe ratio, Maximum Drawdown, and tracking difference.
- Performance breakdown between the equity portfolio component and the futures & cash component.

### `Report.pdf`
AG Capital's professional investment report, comprising:
- **Investment Policy Statement (IPS):** investment objectives, strategies, asset allocation policy, and rebalancing policy for both funds.
- **Portfolio Construction:** U.S. macroeconomic analysis (CPI, Fed policy, GDP, PMI), sector and stock selection rationale for the active fund, and full replication methodology for the passive fund.
- **Monitoring & Rebalancing:** monthly performance tracking, market-driven rebalancing decisions, and application of DJIA Index Futures.
- **Performance & Risk Evaluation:** comprehensive assessment of both funds using risk-adjusted metrics and performance attribution analysis.
- **Conclusions & Limitations:** critical reflection on active versus passive management effectiveness, methodological constraints, and proposed improvements.

## Disclaimer

This project does not constitute investment advice.

