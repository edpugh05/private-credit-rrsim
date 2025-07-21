# Private Credit Risk-Return Simulator

Monte Carlo simulation framework analyzing private credit portfolio performance with live market data integration.

https://imgur.com/a/W6a76c5

## Current Market Data
*Updated: 2025-07-21 22:28:48*

```
• 10Y Treasury: 4.38%
• IG Credit Spread: 0.80%
• HY Credit Spread: 2.93%
• VIX: 16.4
• Fed Funds: 4.33%
• Unemployment: 4.1%
• Market Stress Level: 12.2%
```

## Credit Spread Ladder
```
AAA: 0.24%    BB:  1.76%
AA:  0.40%    B:   2.93%
A:   0.64%    CCC: 6.45%
BBB: 0.96%
```

## Simulation Results
**2000 Monte Carlo simulations across 5 scenarios**

```
Expected Annual Return: 5.2%
Standard Deviation:     0.7%
Sharpe Ratio:          1.16
5% VaR:                4.0%
Probability of Loss:   0.0%
Risk Premium:          80 bps
```

## Scenario Breakdown
```
Current Market:    5.7% (35% probability, worst: 4.9%)
Market Rally:      6.0% (10% probability, worst: 5.2%)
Inflation:         5.1% (20% probability, worst: 4.4%)
Recession:         4.6% (20% probability, worst: 3.9%)
Stress Test:       4.1% (15% probability, worst: 3.3%)
```

## Technical Features
- Live data from 19 market sources (FRED API, Yahoo Finance, web scraping)
- Real-time credit spreads, default rates, and macro indicators
- Institutional-grade risk analytics with dynamic stress testing
- Automated scenario generation based on current market conditions
