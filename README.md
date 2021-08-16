<!-- # Performance-and-Risk-Analysis -->
# Performance and Risk Analysis for Equity Stock

**Introduction**

We made a Python code using Data Science libraries which deals with performance measurement and risk statistics of equity stocks with the objective of identifying the stock with the highest return per unit of risk. 
  
The task can be divided into two parts:

## Capture given equity stocks and respective benchmark

Technical solution should aim to capture given stocks and benchmark along with Start and End Dates for Performance Measurement and Risk Statistics, through a web based interface. After capturing above details, the solution should be able to connect to Yahoo Finance API to get Month End historical 'Adj Close' Price for these stocks and benchmark for the requested Start and End Dates. The interface should be intuitive and should make it easy for capturing the information with minimal scope for erroneous entries.
For the purposes of this problem statement, consider below Tickers for Equity Stocks, which are the list of 5 largest stocks in NDX (Nasdaq-100), a stock market index that measures stock performance of 100 largest non-financial listed companies in United States:
a) AAPL (Apple)
b) MSFT (Microsoft)
c) AMZN (Amazon)
d) FB (Facebook)
e) TSLA (Tesla)
Consider Start Date as 01-Jan-2016 and End Date as 31-Dec-2020 for the purposes of performance measurement (5 years month end data including 31-Dec-2015).

## Create Performance Measurement and Risk Statistics

**Performance Measurement**

Technical Tool should calculate 1M, 3M, 6M, 1Y, 2Y, 3Y and 5Y Cumulative and Annualized Returns as of the end date (31-Dec-2020) for Ticker ‘TSLA’ and Benchmark ‘NDX’. For this the Tool should capture historical Month End 'Adj Close' Prices for the last 5 years and calculate Monthly Returns. Based on Monthly Returns arrived, Cumulative and Annualized Returns should be calculated for multiple periods (1M, 3M, 6M, 1Y, 2Y, 3Y and 5Y) for ‘TSLA’ and Benchmark ‘NDX’.

*Generate below Visualizations:*
Create graph with Stock Price Rebased to 100 based on Cumulative Monthly Returns for last 5 years along with Benchmark. Include all stock Tickers along with Benchmark NDX in a single chart as in illustration.


**Risk Statistics**

Tool should identify the Stock that has the highest return per unit of risk measure as of End Date 31-Dec-2020. Consider below measures for this purpose:
(i) 5 Year Annualized Sharpe Ratio
(ii) 5 Year Annualized Information Ratio


