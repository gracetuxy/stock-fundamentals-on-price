# stock-fundamentals-on-price

### Project Goal
The goal of this project is to examine how company fundamentals — the company’s financial information, such as its revenue, earnings per share, dividends per share, and etc. — impact its share price or its value in FAMO (Facebook, Apple, Microsoft, Oracle) companies. These are four of the most prominent technology companies with consistent growth that historically outperforms the market, and thus, would all theoretically have similarly positive market sentiments. This allows us to hold the public sentiment factor relatively constant while we explore the effects of company fundamentals. Once we are able to explain the relationship between company fundamental and stock price, it opens up the possibility to use our model to make predictions about the future share prices for FAANG companies, which can be valuable to investors.

### Data Source
The dataset we will be using comes from the University of Pennsylvania Wharton Research Data Services (WRDS) center. This dataset is specifically called the CompuStat database and includes a variety of fundamental data from annual 10k report filings, as well as quarterly 10-Q report filings. It includes a wide range of companies that are listed on various exchanges, with data reaching as far back as 1975. The dataset comes quite raw in format, so data preprocessing and cleaning steps have been taken to ensure that the metrics we will be using are clear and organized.


*One important thing to note would be the possibility of correlations between our variables. We did try to pick variables that we thought would give a well-rounded picture of a company’s financial strength, but nonetheless there will be correlations present. In our analysis and report, we will make sure to keep this in mind.*
