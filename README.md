# Portfolio-Management

## Overview

Our team acted as portfolio managers at a simulated asset management firm. The objective was to construct, manage, and evaluate two mutual funds benchmarked against the Dow Jones Industrial Average (DJIA):

* **Active Fund:** A Large-Cap Value portfolio designed to outperform the DJIA on a risk-adjusted basis.
* **Passive Fund:** A full-replication portfolio designed to closely track the DJIA while minimizing tracking error.

Both funds started with a notional capital of **USD 50 million** and were managed over the period from **May 2025 to May 2026**. The project covers portfolio construction, rebalancing decisions, futures-based exposure management, and performance evaluation.

## Repository Contents

### `Active Fund Calculation Code.ipynb`

This notebook contains the complete implementation of the active portfolio strategy, including:

* Data collection and preprocessing.
* Macroeconomic and sector analysis inputs.
* Stock selection based on a Large-Cap Value philosophy.
* Black-Litterman portfolio optimization.
* Portfolio rebalancing analysis.
* Performance attribution.
* Risk and return evaluation.

### `Passive Fund Calculation Code.ipynb`

This notebook contains the implementation of the passive portfolio strategy, including:

* DJIA full-replication portfolio construction.
* Benchmark tracking methodology.
* Tracking error and tracking difference calculations.
* DJIA futures overlay implementation.
* Portfolio monitoring and rebalancing.
* Performance comparison against the benchmark.

### `Report.pdf`

The final investment report summarizing the entire fund management process, including:

* Investment Policy Statements (IPS).
* Market and macroeconomic outlook.
* Active and passive portfolio construction methodologies.
* Rebalancing decisions and rationale.
* DJIA futures hedging strategy.
* Performance and risk evaluation.
* Performance attribution analysis.
* Reflections, limitations, and key findings.

## Disclaimer

This project does not constitute investment advice.

