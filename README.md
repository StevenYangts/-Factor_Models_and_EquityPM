# **Project Overview**<br>
This project focuses on the factor exposure analysis of individual securities and portfolios, employing both static and rolling regression techniques using the Fama-French 3-Factor Model and the Carhart 4-Factor Model. Additionally, the project extends these multi-factor models to equity portfolio management.

# **Key Features**<br>
### **1. Factor Exposure Analysis<br>**

Explore both static and rolling factor exposure of various securities using:

Fama-French 3-Factor Model

Carhart 4-Factor Model

### **2. Equity Portfolio Management<br>**

Functions developed to generate equity portfolios for given stock tickers and their corresponding weights.<br>

Portfolio Factor Exposure: Calculate the overall factor exposure of a portfolio based on the factor loadings of individual stocks. <br>

Risk Decomposition: Decompose portfolio risk into <br>
1. Common Factor Variance<br>
2. Specific (Idiosyncratic) Variance

### **3. Performance and Risk Metrics<br>**

The project includes basic functions to calculate portfolio-level performance and risk metrics, such as:

- Sharpe Ratio<br>
- Sortino Ratio<br>
- Calmar Ratio<br>
- Max Drawdown<br>
- Parametric VaR<br>
- Parametric CVaR<br>
- Historical VaR<br>
- Historical CVaR<br>

# **Data Files & Data Source** <br>

Source: Yahoo Finance, Kenneth French dataset  <br>

start_date = '2019-05-28' <br>
end_date = '2024-03-28'<br>
