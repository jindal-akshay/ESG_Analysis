# Project-1-Fintech

# Sustainable Investing vs Index Fund Investing

## Team Members:
- David Still
- Anton Diez
- Akshay Jindal
- Moses Devanesan

# Topic of the Analysis:
Is there a price to be paid by investing in ESG mutual funds? How do mutual funds with high sustainability ratings perform against the S&P 500? 

# Hypothesis:
 Actively managed mutual funds tend to underperform passively managed or index funds on a regular basis. S&P Down jones Indices released a report in 2019 and found that 85.1% of actively managed large-cap funds lagged the S&P 500 over a 10 year period:

  ![% of funds underperform](https://fm-static.cnbc.com/awsmedia/chart/2019/2/15/pisani1.1552668684661.png? "% of funds underperform") 

Since sustainable funds need to be actively managed in order to select companies that meet certain criteria, our team surmised that at least 50% of the sustainable funds will underperform the S&P 500 over a 10 year period. 

If an investor feels that sustainable investing is important, how much will it cost them in returns? Will investors in sustainable funds have to deal with lower performance and higher volatility? 

Out of 129 funds that we analyzed, the S&P 500 had the 13th highest annual return between 2010 and 2020 at 11.2%. The average return for the entire group was 6.9%. This would seem to indicate that there is a large opportunity cost for people investing in sustainable funds unless you happened to have chosen one of the top performing ones. 

Perhaps more surprisngly, the ESG score for the S&P 500 was similar to the ESG scores of the top performing mutual funds. Of the top 20 funds with the highest sustainability scores, only 5 of them had sustainability mandates. This would seem to indicate that some, if not many, of the components of the S&P 500 have already undertaken sustainability intiatives. 

# How we Performed the Analysis

Barron's provided a list of the large-cap mutual funds that received an "above average" or "high" sustainability rating from Morningstar. 

Taking this information from Barron's, our group compiled the daily closing prices from 2010-2020 from Bloomberg to see how these funds performed over a 10 year time period. To further our analysis, the group collected the ESG rankings and various value & growth measures (i.e. P/E ratio, ) from Morningstar to better understand how the characteristics of the sustainable funds. 

Altogether the team utlized 4 different data sets from Barron's, Morningstar and Bloomberg. This data was concatendated into one dataframe to do our analysis. 

# Data Cleanup & Exploration
T


# Key Questions

## How does investing in ESG companies affect return on investment? 
## How do companies with strong ESG policies compare to respective benchmark (i.e S&P 500, MSCI ESG ETF)?
## What are the typical financial ratios, for instance (P/E Ratio, ROI, leverage) of ESG companies?
## What are the risk clasifications of the ESG companies? (i.e Value, Growth) 
## What are the qualitative factors for ESG companies? 
####	Sector, multi-national/domestic, location/regions, market cap, # of employees
## How does 'Executive pay' play a role in ESG companies?
## With the companies in different sectors, which ones are outperforming/have strong ESG policies? 
## The companies in other sectors that have “low scores”, which companies are leading?


# DATA
## API
### EDGAR (SEC data)

## Balance Sheet
###  Bloomberg, Quandl, Yahoo Finance, SEC EDGAR, MSCI

## Plotting
### Mapping (plotly express)
### Quantitative presentation (plotly, hvplot)


​

Sources:
  
  1.  https://www.cnbc.com/2019/03/15/active-fund-managers-trail-the-sp-500-for-the-ninth-year-in-a-row-in-triumph-for-indexing.html
​