# Delta Hedging & Adversarial Stock Path Generation Simulator

A quantitative finance project built during the AlgoZenith HFT Bootcamp to compare traditional Black–Scholes delta hedging with neural network based hedging under different market conditions.

## What it does

- Simulates 10,000+ synthetic stock price paths using Geometric Brownian Motion
- Prices European call options using the Black–Scholes model
- Computes Greeks and Implied Volatility
- Implements dynamic delta hedging and neural network based hedging
- Evaluates performance using P&L, VaR and CVaR

## Tech Stack

Python • TensorFlow • NumPy • Pandas • SciPy • Matplotlib

## Files

```
Adversarial_Stock_Path_Generation_Simulator.ipynb
20260204_option_minute_prices_non_expiry.csv
20260205_option_minute_prices_expiry.csv
```

## Future Work

- Add transaction costs
- Stress testing under extreme market conditions
- Compare against no-hedging strategies
- Convert notebook into a modular Python project
