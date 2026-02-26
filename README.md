# Exploratory-data-analysis-of-two-investments-using-yahoo-finance-data-yfinance-API-
(Please note that this project is not complete but offers information on Python programming, use of APIs, Econometric data practices and constructing an equally weighted portfolio with an adjustable number of investments)

Compare individual assets or combine multiple assets into equally weighted portfolios. Then assess log-returns by collecting data using the yfinance API. Finally, assess distributions of log-returns, compare ECDFs, Skewness and Kurtosis to get a more holistic view on market volatility between the two investments. Steps can be explained if you wish to reach out to me. 

Once ran, the API tracks the last 5-years of closing prices which are transformed to log-returns. Data scraping can be changed to any number of months, days or years but 5 years is recommended. It is crucial that both potential investments of interest have the same time duration.

In this case, all trading days from 26/02/2021 to 26/02/2026 are used. Void cells are removed so the program can run with no missing data which is not uncommon due to weekends or public holidays. Hence there is roughly 252 observations of trading days per year. 

Blue lines represents the undiversified portfolio. Constructed of five publically listed FTSE equities. Involving: four Insurance companies and one Bank. All equally weighted with a coefficient of 0.2.   

Orange lines represents a passive investment involving the entire FTSE Index.  
