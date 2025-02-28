Task 1: Preprocess and Explore the Data

Load, clean, and understand the data to prepare it for modeling.
Extract historical financial data using YFinance for :
TSLA provides potential high returns with high volatility.
BND contributes stability and low risk.
SPY offers diversified, moderate-risk market exposure.
Data cleaning and Understanding.
Check basic statistics to understand the distribution of the data.
Ensure all columns have appropriate data types and check for missing values.
Handle missing values by either filling, interpolating, or removing them.
Normalize or scale the data if required, especially for machine learning models.
Conduct Exploratory Data Analysis (EDA):
Visualize the closing price over time to identify trends and patterns.
Calculate and plot the daily percentage change to observe volatility.
Analyze volatility by calculating rolling means and standard deviations to understand short-term trends and fluctuations.
Perform outlier detection to identify significant anomalies.
Analyze days with unusually high or low returns.
Seasonality and Trends:
Decompose the time series into trend, seasonal, and residual components (e.g., using statsmodels).
Analyze Volatility
Calculate rolling means and standard deviations to understand short-term trends and volatility.
Document key insights like overall direction of Tesla’s stock price, Fluctuations in daily returns and their impact, VaR and Sharpe Ratio to assess potential losses and risk-adjusted returns.
