# Tableau-Dashboard
![logo](https://github.com/Aisharriya/Tableau-Dashboard/blob/main/tableau.png)
# Comprehensive Stock Market Analysis of Leading Tech Giants

This project provides a comparative analysis of stock performance among six prominent technology companies—Apple, Facebook, Google, Nvidia, Tesla, and Twitter—spanning from January 2016 to April 2020. Using a structured data warehouse and interactive Tableau dashboards, this study explores price trends, trading volume, and performance metrics across these industry leaders.

## Project Objectives

The main goals of this project are:
1. To analyze the historical stock performance of each company.
2. To uncover patterns in trading volume, price movements, and volatility.
3. To develop visual insights that support strategic investment decisions.
4. To highlight the influence of market events on individual stocks.

## Data Overview

- **Dataset Source**: Kaggle dataset containing daily stock data.
- **Key Variables**: Open and close prices, daily highs and lows, trading volume, and adjusted close prices, enabling comprehensive trend analysis.
- **Data Architecture**: The data is structured using a star schema within a data warehouse, optimized with fact and dimension tables:
  - **Fact Table**: Captures daily stock metrics (open, high, low, close prices, trading volume).
  - **Dimension Tables**: Includes date and company dimensions for easy filtering and analysis.

## System and Market Limitations

Challenges in data processing, complex query execution, and real-time analysis are acknowledged in this study, highlighting the importance of efficient data handling frameworks to overcome performance bottlenecks in high-frequency stock data environments.

## Visualizations and Insights

This project leverages Tableau dashboards to present critical financial insights:

1. **Stock Price Trends**:
   - Line charts visualize the opening, closing, high, and low prices, highlighting both short-term fluctuations and long-term price trends. These charts help identify market reactions to key events (e.g., product launches, earnings reports).

2. **Trading Volume Analysis**:
   - Bar graphs illustrate daily trading volumes, showing how volume correlates with price changes. Peaks in trading activity often coincide with major company or industry events, informing buy/sell timing.

3. **Performance Comparison**:
   - Comparative bar charts and radar charts enable side-by-side performance analysis of the companies, focusing on stock price changes, volatility, and trading volume.

4. **Price Change Distribution**:
   - A distribution chart demonstrates the frequency of percentage price changes, with Tesla and Twitter exhibiting the highest volatility. In contrast, Apple, Google, and Facebook show stability, with price changes clustered around 0%.

5. **Moving Averages**:
   - Using 50-day and 200-day moving averages, charts display longer-term trends and price momentum. Key indicators like Golden Cross and Death Cross patterns are identified, providing buy/sell signals over the analysis period.

6. **Custom Dashboards**:
   - Each company has its own dashboard in Tableau, detailing unique trends and patterns specific to its stock. For example, Tesla’s dashboard highlights high volatility, while Twitter’s charts show sensitivity to external events.

## Key Findings
- **Volatility**: Tesla and Twitter stocks exhibit high volatility, making them riskier investments, while Apple, Google, and Facebook maintain relative stability.
- **Trading Volume Trends**: Apple shows the highest consistent trading volume, with Twitter displaying significant peaks in response to market sentiment.
- **Long-Term Trends**: Moving averages reveal overall upward momentum despite periodic downturns, such as the market correction in 2018.

## Conclusion
This analysis demonstrates the value of a structured data warehouse for organizing stock market data and the power of visualization tools like Tableau to turn complex datasets into actionable insights. Investors and analysts can leverage these insights to make informed decisions, mitigate risks, and capitalize on market opportunities.
