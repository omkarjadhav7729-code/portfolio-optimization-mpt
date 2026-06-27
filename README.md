# portfolio-optimization-mpt
Python-based portfolio optimization using Modern Portfolio Theory and Sharpe Ratio analysis.

This project implements **Modern Portfolio Theory (MPT)** in Python to optimize a portfolio of Indian banking stocks using **Monte Carlo Simulation**. The model analyzes historical stock price data to calculate expected returns, risk (volatility), and the Sharpe Ratio, ultimately identifying portfolios that offer the best risk-adjusted returns.

The project demonstrates the practical application of quantitative finance concepts such as diversification, covariance, correlation, and risk-return optimization.

---

## Objectives

- Analyze historical stock price data.
- Calculate annual returns and annual volatility.
- Generate thousands of random portfolios using Monte Carlo Simulation.
- Compute the Sharpe Ratio for each portfolio.
- Identify:
  - Maximum Sharpe Ratio Portfolio
  - Minimum Volatility Portfolio
- Visualize the risk-return trade-off using the Efficient Frontier.

---

## Stocks Used

- AXISBANK.NS
- HDFCBANK.NS
- ICICIBANK.NS
- KOTAKBANK.NS
- SBIN.NS

---

## Methodology

The project follows the workflow below:

1. Download historical stock price data using Yahoo Finance.
2. Calculate daily percentage returns.
3. Compute:
   - Annual Returns
   - Annual Volatility
   - Covariance Matrix
4. Generate 10,000 random portfolios using Monte Carlo Simulation.
5. Calculate portfolio:
   - Expected Return
   - Volatility
   - Sharpe Ratio
6. Identify:
   - Portfolio with Maximum Sharpe Ratio
   - Portfolio with Minimum Volatility
7. Visualize portfolio performance and optimal asset allocation.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Jupyter Notebook

---

## Visualizations

This project includes:

- Monte Carlo Portfolio Simulation
- Efficient Frontier Visualization
- Maximum Sharpe Portfolio
- Minimum Volatility Portfolio
- Optiml Portfolio Allocation (Bar Chart)
- Correlation Matrix Heatmap

---

## Key Concepts Applied

- Modern Portfolio Theory (MPT)
- Portfolio Diversification
- Expected Return
- Annualized Volatility
- Covariance Matrix
- Correlation Matrix
- Sharpe Ratio
- Monte Carlo Simulation
- Risk-Return Optimization

---

## Key Learnings

Through this project, I gained practical experience in:

- Financial data analysis using Python
- Portfolio optimization techniques
- Applying quantitative finance concepts to real market data
- Monte Carlo Simulation
- Data visualization using Matplotlib
- Working with Pandas and NumPy for financial analysis

---

## Disclaimer

This project is intended for educational purposes only and should be considered as nothing more than a project.

---

## Author

**Omkar Jadhav**

MBA Candidate | Finance Enthusiast | Aspiring Credit & Risk Analyst

LinkedIn: https://www.linkedin.com/in/omkar-jadhav-060233259/
