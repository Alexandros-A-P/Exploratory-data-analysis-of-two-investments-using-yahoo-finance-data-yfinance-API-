# Exploratory-data-analysis-of-two-investments-using-yahoo-finance-data-yfinance-API-
Compare individual assets or combine multiple assets into equally weighted portfolios. Then assess log-returns by collecting data using the yfinance API. Finally, assess distributions of log-returns, compare CDFs, Skewness and Kurtosis to get a more holistic view on market volatility between the two investments. Steps can be explained if you wish to know more. 

Once ran, the API tracks the last 5-years of closing prices which are transformed to log-returns. This can be changed to any number of months, days or years but 5 years is recommended. It is crucial that both assets of comparison have the same time duration. In this case, all trading days from 26/02/2021 to 26/02/2026 are used. Void cells are removed so the program can run with no missing data. 

The Blue line represents an undiversified portfolio. Constructed of five publically listed FTSE equities. Involving: four Insurance companies and one Bank. All equally weighted with weight equal to 0.2 of Portfolio   

The Orange line represents a passive investment involving the entire FTSE Index.  
