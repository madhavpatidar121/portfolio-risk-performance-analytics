# Portfolio Risk & Performance Analytics

### Python | Portfolio Management | Risk Analytics | Monte Carlo Simulation

## Project Overview

Developed a Python-based analytical framework to evaluate the performance and risk characteristics of a hypothetical $100,000 equity portfolio against the S&P 500 ETF (SPY), using 2025 historical market data.

The project integrates portfolio performance measurement, benchmark-relative analysis, downside risk assessment, and Monte Carlo simulations.

## Portfolio Allocation

| Stock | Weight |
|---|---:|
| Microsoft (MSFT) | 40% |
| Apple (AAPL) | 35% |
| JPMorgan Chase (JPM) | 25% |

## Key Results

| Performance Metric | Result |
|---|---:|
| Portfolio Total Return | 21.17% |
| SPY Total Return | 18.01% |
| Portfolio Outperformance | +3.16 percentage points |
| Annualized Volatility | 22.36% |
| Sharpe Ratio | 0.80 |
| Information Ratio | 0.33 |
| Beta | 1.03 |
| Jensen's Alpha | +2.88% |
| Maximum Drawdown | −22.27% |

## Downside Risk Analysis

| Risk Metric | Result |
|---|---:|
| 95% Daily VaR | 1.80% |
| 99% Daily VaR | 3.66% |
| 95% Daily CVaR | 3.05% |
| 99% Daily CVaR | 5.28% |

The portfolio experienced a maximum drawdown of 22.27%, with the trough occurring on April 8, 2025.

## Monte Carlo Simulation

Performed 5,000 Monte Carlo simulations over a 252-trading-day horizon.

| Simulation Metric | Result |
|---|---:|
| Mean Ending Value | $124,749.60 |
| Median Ending Value | $121,421.12 |
| 5th Percentile | $85,112.14 |
| 95th Percentile | $175,292.15 |
| Simulated Probability of Profit | 81.16% |
| Simulated Probability of Loss | 18.84% |

## Investment Insights

**Benchmark Outperformance:** The portfolio generated 3.16 percentage points of excess compounded return over SPY during 2025.

**Risk-Adjusted Performance:** Positive Jensen's alpha and a Sharpe ratio of 0.80 indicate favorable historical risk-adjusted performance under the model assumptions.

**Downside Exposure:** Despite strong annual returns, the portfolio experienced a 22.27% maximum drawdown, demonstrating the importance of evaluating interim losses alongside total returns.

**Monte Carlo Analysis:** Simulated outcomes suggest a wide range of potential ending values, emphasizing uncertainty in forward-looking portfolio projections.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib
- yfinance
- Google Colab

## Methodology and Limitations

- Historical period: January–December 2025.
- Portfolio assumes daily rebalancing to fixed target weights.
- Transaction costs and taxes are excluded.
- Historical adjusted closing prices are used.
- Annualized arithmetic returns and volatility assume 252 trading days.
- A 4% annual risk-free rate is assumed.
- Monte Carlo simulations assume normally distributed daily returns with parameters estimated from historical data.
- Historical tail-risk estimates, particularly at 99% confidence, are limited by the one-year sample.
- Historical and simulated performance do not guarantee future investment results.

## Project Notebook

Open `Portfolio_Risk_Performance_Analytics.ipynb` in this repository to review the complete Python code, charts, and analytical outputs.

*This project is intended for educational and investment research demonstration purposes. 
