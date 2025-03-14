# Monte Carlo Portfolio Risk Analysis (US Stocks)

## Overview
This repository demonstrates a Monte Carlo simulation for portfolio risk assessment using historical stock data from **US tech companies**. The simulation estimates expected returns, volatility, Value at Risk (VaR), and Expected Shortfall (CVaR).

## Objectives
- Simulate portfolio returns using Monte Carlo methods.
- Calculate risk metrics: Expected Return, Volatility, VaR, and Expected Shortfall.
- Provide clear visualizations of risk distribution.

## 📁 Project Structure
```
monte-carlo-portfolio-risk/
│── data/
│   │── us_stocks_data.csv          # US stock price data
│── notebooks/
│   │── monte_carlo_simulation.ipynb
│── src/
│   │── monte_carlo_simulation.py   # Python script
│── results/
│   │── monte_carlo_results.csv     # Simulation results
│── README.md
```

## Installation & Usage
**Install Dependencies:**
```bash
pip install numpy pandas matplotlib seaborn yfinance
```

**Run the analysis notebook:**
```bash
jupyter notebook notebooks/monte_carlo_simulation.ipynb
```

## Analysis Steps
-**Fetch historical stock data** for AAPL, MSFT, GOOGL, AMZN, and TSLA.  
-**Compute daily returns** and portfolio statistics.  
-**Run Monte Carlo simulations** (10,000 iterations) to model portfolio returns.  
-**Calculate risk metrics** (VaR and Expected Shortfall).  
-**Visualize portfolio return distribution** with risk thresholds.

## Results & Visualization
- **Histogram** of simulated portfolio returns.
- **95% Value at Risk (VaR)** marked in red.
- **Expected Shortfall (Conditional VaR)** for worst-case scenarios.

## Future Enhancements
- Add stress-test scenarios.
- Test different portfolio weight allocations.
- Extend with real-time market data feeds.

## License
This project is licensed under the MIT License.

