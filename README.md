# Bank of England Monetary Policy Event Study

## Overview

This project examines how UK bank equities respond to Bank of England Monetary Policy Committee (MPC) decisions.

The analysis uses an event-study framework to measure abnormal and cumulative abnormal returns around monetary policy announcements.

## Research Question

How do UK bank stocks respond to Bank of England interest-rate decisions, and does the market reaction differ between rate hikes, cuts and holds?

## Data

- UK bank equities: Barclays, HSBC, Lloyds Banking Group and NatWest
- Market benchmark: FTSE 100
- Period: January 2022 – August 2026
- Monetary policy events: Bank of England MPC decisions

## Methodology

The project applies a market-model event study to estimate expected stock returns and abnormal returns around MPC announcements.

Key methods include:

- Daily stock returns
- Market-model estimation
- Alpha and beta estimation
- Abnormal returns
- Cumulative abnormal returns (CAR)
- Event windows of (-1,+1) and (-5,+5)
- t-tests
- ANOVA
- Correlation analysis
- Regression analysis

## Key Findings

The analysis found positive cumulative abnormal returns across the full sample around the (-5,+5) event window.

The average CAR across 36 MPC events was approximately 2.57%, with a statistically significant t-test result (p = 0.0063).

Mean CAR differed across policy decisions:

| Decision | Mean CAR |
|---|---:|
| Cut | 3.94% |
| Hold | 3.38% |
| Hike | 0.87% |

However, the ANOVA test did not find a statistically significant difference between the three decision categories (p = 0.355).

## Visualisations

### Relative Performance

relative performances.png

### Abnormal Returns Around MPC Decisions

Abnormal Returns .png

### Cumulative Abnormal Returns

[Cumulative Abnormal Returns.png](https://github.com/aakriitii-s/boe-uk-bank-event-study/blob/d12880960de1ab3fd5c5c97959c5f6d917eee0bc/Cumulative%20Abnormal%20Returns.png)

## Tools

Python, Pandas, NumPy, Matplotlib, SciPy, Statsmodels

## Skills Demonstrated

Financial data analysis · Event studies · Econometrics · Statistical testing · Data visualisation · Python · Financial markets
