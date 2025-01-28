

# Time Series Analysis Notebooks
This repository contains Jupyter notebooks for time series analysis using Python, demonstrating various techniques for analyzing and visualizing stock prices and trading volumes. The notebook focuses on stock data for companies like Google (GOOGL), Tesla (TSLA), Ford, and GM.
#### Description 
This notebook covers the analysis of stock prices and trading volumes for Google (GOOGL) and car companies (Tesla, Ford, and GM) over a specified time period. The analysis utilizes techniques like data retrieval, basic exploration, moving averages, volatility analysis, and more.
Key topics include:
- Data retrieval using `pandas_datareader`
- Basic data exploration and visualization
- Volume traded analysis
- Market capitalization calculation
- Moving averages (simple and exponential)
- Correlation and scatter matrix
- Daily percentage change
- Volatility analysis
- Box plots
- Cumulative returns
- Rolling and expanding windows
- Time period-specific analysis
#### Key Sections
- **Data Retrieval**: Retrieves stock data for Google, Tesla, Ford, and GM using `pandas_datareader`.  - **Basic Data Exploration**: Displays the first few rows and descriptive statistics of the data.
- **Volume Traded and Interpretations**: Analyzes the volume traded for each stock and identifies significant trading days.
- **Market Cap Calculation**: Calculates the approximate market capitalization based on the open price and volume.
- **Moving Averages**:  - Computes and plots the 50-day simple moving average for Tesla's stock price.  - Computes and plots the 30-day and 10-day rolling mean for Tesla's stock price.  - Computes and plots the exponential moving average with different smoothing factors.  - Computes and plots the exponential weighted moving average for Tesla's stock price.
- **Correlation and Scatter Matrix**: Analyzes the correlation between the stock prices of Tesla, GM, and Ford.
- **Daily Percentage Change**: Calculates the daily percentage change in stock prices.
- **Volatility Analysis**: Analyzes the volatility of stock returns using histograms and KDE plots.
- **Box Plots**: Creates box plots to compare the returns of Tesla, GM, and Ford.
- **Cumulative Returns**: Computes and plots the cumulative returns for each stock.
- **Rolling and Expanding Windows**: Computes and plots rolling and expanding averages for Tesla's stock price.
- **Time Period-Specific Analysis**: Analyzes stock prices for specific time periods and customizes plots to observe trends or fluctuations during those periods.
Feel free to explore the notebook and modify it for your own time series analysis projects!
