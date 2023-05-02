# Main Title
Using Yahoo finance API, we will be analyzing the stock market and its correlation to the economy. We will be looking at the stock market as a whole and then breaking it down into sectors. We will be looking at the correlation between the indexes, sectors and stocks market.


## Questions:
 
 ​1. Report 1 Aims to answer the question: How does the stock market correlate to the economy? Indexes to Sectors - which sectors are most correlated to which indexes? Stocks to sectors - which stocks most correlated to which sectors? Stocks to Indexes - which stocks are most correlated to which indexes? How do these correlations change over key market time periods? 
<br />
<br />
2. Report 2 aims to answer the question: What is the rank for best quality value in growth stocks based on fundamental metric analysis? What is the correlations between stock returns and the fundamental metrics.
<br />
<br />
3. Report 3 aims to answer the question: What are the best basket of securities to invest in based on fundamental metric analysis? What is the correlations between stock returns and the fundamental metrics. What is the optimal investment portfolio to maximize returns and minimize risk for a given return time frame using the Sharpe ratio?

# Report 1

## Market Statistics Report

TIME SERIES ANALYSIS, CORRELATIONS, SHARPE RATIOS

1. Index, sector and stock performance statistics (selected equities):
    * Returns
    * Standard deviation
    * Correlation
    * Sharpe Ratios
    * Company Fundamentals Summary

<br/>

2. Static and Time Series Analysis of metrics above by population segments: indices sectors and stocks. 
    - Indexes
        - 4 major indexes 
    - Sectors 
        - 8-10 key market sectors 
    - Stocks
        - 95 stock list
<br/>
<br/>
3. Correlation analysis - MARKET AND STOCKS � Understanding Relationships
    1. Indexes to Sectors - which sectors are most correlated to which indexes? 
    2. Stocks to sectors - which stocks most correlated to which sectors?
    3. Stocks to Indexes - which stocks are most correlated to which indexes? 
    4. How do these correlations change over key market time periods? 

4. Sharpe Ratio Analysis:
    - Rank order stocks by Sharpe Ratios 
    - Analyze ratio across sectors and time. 

5. Statistical Metrics - STOCKS AND OPTIONS (Calls/Puts)**
    1. Stocks and select options for select time periods.
    2. 70, 50 and 30 delta options
    3. 0 DTE, 5 DTE, 15 DTE, 30 DTE, 60 DTE
    4. Analyze returns, standard deviation, correlation and Sharpe ratios for select options vs. stocks.


# Report 2

## STOCK EARNINGS AND FUNDAMENTALS REPORT


ARNINGS TRADE ANALYSIS
* Company/Sector Fundamental Analysis:
### Value Metrics
* P/E 
* P/S
* P/B
### Growth Metrics
* EPS Growth Rates � 1 year
* EPS Growth Rates � 5 year
* PEG Ratio
### Accounting Returns and Margins
* ROA
* ROE
* ROI
* Gross/Net Margins
### Earnings**
* Revenue surprise - Y/N
* Revenue surprise % +/-
* Earnings surprise - Y/N
* Earnings surprise % +/-
----------------------------------------
### Earnings returns Hypothesis Analysis
- Null Hypothesis:  There is no difference in Risk/Returns/Sharpe Ratio within the quarterly earnings window (+/- 10 trading days) vs outside the earnings window (172 days)
- Alternative Hypothesis:  There is a difference between key statistical metrics within the +/- 10-day quarterly window vs. outside the earnings window
----------------------------------------
### Analyze:
* Returns
* Standard deviation
* Sharpe Ratio
* Earnings Report Surprises:
* Revenue
* EPS
## Forward Guidance
- Within 80 earnings period trading days vs. 172 outside earnings trading days


# Report 3

## PORTFOLIO ANALYSIS

### Based on the analysis above, given stock returns and risks, what is the optimal investment portfolio to maximize returns and minimize risk for a given return timeframe:
- 6 months
- YTD
- 1 year
- 3 year
- 5 year
- 10 year 

#### Looking to maximize Sharpe ratio, maximize returns and minimize risk


# Report 4 (Optional)

## MARKET TREND REPORT**

- Weekly reports around bullish, bearish and neutral trending sectors and stocks
- Apply basic trend rule logic to charts to isolate best potential trading opportunities.
- Looking at daily, 6 month charts only
- Utilize three basic indicators: EMA's, squeeze, Bollinger bands
- SMA's aligned?  
    - 8 above 21, 21 above 50, 50 above 200?
- Any Squeeze indicator opportunities?
- SMA/s trending up for bulls, down for bears, flat for neutral
- Instead of eyeballing, use rules-based criteria to define trends and codify reports



## Notebooks
- [JUPYTER LAB NOTEBOOK LINK](./main.ipynb)
- [Final Analysis](./file.ipynb)

## Plots
- PLOTS WILL GO HERE 

---
​
![Plot1](./assets/images/plot_image.png)
​
​
## Explanation

### Analysis Conclusion:
- 
​

## Additional Research Topics
- 


## Getting Started

### Prerequisites
​
​You must have Python 3 installed

```
python3 --version
```

You must have Anaconda installed
```
$ anaconda --version
```


### Install Environmnet
```
conda create -n <env_name> python=3.7 anaconda
```

### Clone/Run Repository
```
git clone ...
```

## Built With

- [![Python 3.7.13](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]([https://www.python.org/downloads/release/python-3713/)
[![Python](https://img.shields.io/badge/Python-3.7.13-blue)](https://www.python.org/downloads/release/python-3713/) - Programming Language
- [![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/docs/#) - Data maniupulation library
- [![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/) - Multi-dimensional array library
- [![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/python/) - Visualization library for plots
- [Hvplot](https://hvplot.holoviz.org/) - Visualization library for Pandas-based plots
- [Geoviews](https://geoviews.org/#) - Visualization library for geographic data
- [Seaborn](https://seaborn.pydata.org/)  - Visualization library for statistical plots

## Authors
- **Varoujan John Khorozian** - [LinkedIn](https://www.linkedin.com/in/varoujan-khorozian/) | [Github](https://github.com/vkhorozian)
- **Kirill Chugunov** - [LinkedIn](https://www.linkedin.com/in/kirill-chugunov-b680811a4/) | [Github](https://github.com/OddMerchantStudios)
- **Hiren Patel** - [LinkedIn](https://www.linkedin.com/in/hdpatel/) | [Github](https://github.com/hpnhs25)
