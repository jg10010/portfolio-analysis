# Portfolio Analysis & Risk Assessment

A quantitative analysis of a five-asset technology portfolio (Tesla, Nvidia, Microsoft, Palantir, Meta) built in Excel. The project applies Modern Portfolio Theory to compute the portfolio's risk-return profile and quantify the diversification benefit of combining imperfectly correlated assets.

## Overview
The portfolio uses a 30/25/25/10/10 allocation strategy across five technology stocks. Daily returns, variance, standard deviation, and a covariance matrix were computed to model the portfolio's overall risk. The observed portfolio variance was then compared to the theoretical variance assuming perfect correlation — the difference quantifies the benefit of diversification.

## Portfolio Allocation
| Asset | Weight |
|-------|--------|
| Tesla | 30% |
| Nvidia | 25% |
| Microsoft | 25% |
| Palantir | 10% |
| Meta | 10% |

The allocation balances established industry leaders (Microsoft, Nvidia, Meta) with targeted exposure to high-growth assets (Tesla, Palantir).

## Methodology
1. **Data collection** — Historical daily prices for all five stocks
2. **Returns** — Daily returns computed for each asset
3. **Statistics** — Mean, variance, and standard deviation per asset
4. **Risk modeling** — 5×5 covariance matrix built from pairwise asset returns
5. **Portfolio metrics** — Weighted expected return, variance, and standard deviation
6. **Diversification analysis** — Compared actual portfolio variance to theoretical variance under perfect correlation

## Key Results
| Metric | Value |
|--------|-------|
| Expected Portfolio Return | $315.70 |
| Portfolio Variance | 1,767.34 |
| Portfolio Standard Deviation | 42.04% |
| Theoretical Variance (Perfect Correlation) | 2,134.33 |
| **Diversification Benefit** | **367.0 (variance reduction)** |

The portfolio's variance was meaningfully lower than the theoretical maximum under perfect correlation — a direct, quantified demonstration that combining imperfectly correlated assets reduces overall risk without sacrificing return.

## Files
- `Portfolio-Analysis-Report.pdf` — full written report with charts and conclusions
- `portfolio-analysis.xlsx` — Excel workbook with raw data, formulas, and covariance matrix

## Skills Demonstrated
- Financial statistics: returns, variance, standard deviation, covariance
- Modern Portfolio Theory and diversification
- Excel modeling (formulas, matrix calculations, charts)
- Technical writing and communication of quantitative results

## Next Steps
- Use Excel Solver to identify the Minimum Variance and Maximum Sharpe Ratio portfolios
- Benchmark returns against XLK (Technology Select Sector SPDR Fund) and the S&P 500
- Expand to additional asset classes (bonds, international equities, commodities)

## Author
Jaideep Gill — [github.com/jg10010](https://github.com/jg10010)
