# Portfolio Optimization and Multifactor Return Analysis

### Description
This project uses Python to construct and optimize global equity portfolios based on Markowitz's Modern Portfolio Theory. It then analyzes the portfolio's excess returns using the Fama-French 3-factor model to identify the key drivers of performance beyond the general market.

### Technologies & Models Used
* **Languages/Libraries:** Python (pandas, numPy, matplotlib) 
* **Financial Models:**
    * Modern Portfolio Theory (Markowitz) 
    * Fama-French 3-Factor Model
    * Capital Asset Pricing Model (CAPM)

### Key Outcomes & Analysis
* Constructed portfolios targeting both minimum variance and maximum Sharpe ratio under short-selling and no-short-selling constraints.
* Performed multifactor regression using the Fama-French model, analyzing the impact of market, size (SMB), and value (HML) factors.
* Demonstrated a **23% increase in explanatory power** over the standard CAPM, validated by a higher R-squared value and statistically significant factor loadings[cite: 49].
* Benchmarked portfolio performance against the NIFTY 50, deriving allocation strategies from risk-adjusted returns and factor exposure insights.
