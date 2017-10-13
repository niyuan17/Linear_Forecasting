# Linear_Forecasting
## Dave Hamilton, Yuan Ni, Kaili Li
A Project Verifying Hull and Qiao’s Paper On Market Timing


## A. Data Description
1.Dividend-Price Ratio (DP)

-log of a twelve-month moving sum of dividends paid on the S&P 500 index minus the log of S&P 500 prices
-source: http://www.multpl.com/

2.Price-to-Earnings Ratio (PE)

-the price divided by earnings over the last 12 months
-source: http://www.multpl.com/

3.Book-to-Market Ratio (BM)

-book value of the S&P 500 divided by the S&P 500 index
-source: Bloomberg

4.Cyclically Adjusted Price to Earnings Ratio (CAPE)

-price divided by the average inflation adjusted earnings over the last ten years    
-source: http://www.multpl.com/

5.Principal Component of Price Ratios (PCAprice)

-the largest principal component of these variables  
-source: calculated in calculateFirstPC.ipynb

6.Bond Yield (BY)

-the 10-year Treasury bond yield divided by the bond yield EMA    
-source:Quandl

7.Default Spread (DEF)

-the difference between Baa yield and Aaa yield    
-source:Quandl

8.Term Spread (TERM)

-the yield difference between the 10-year Treasury Note and the three-month Treasury Bill    
-source:Quandl

9.Cointegrating Residual of Consumption, Assets, and Wealth (CAY)

-cointegrating residual of log consumption, assets, and wealth
-source: http://faculty.haas.berkeley.edu/lettau/data_cay.html

10.Sell in May and Go Away (SIM)

-SIM = d/130, in which d is the number of days in the next 130 business days that lie between the second business day in May and the 15th business day of October  
-source:calculated in calculateSIM.ipynb

11.Variance Risk Premium (VRP)

-VIX minus the volatility forecast from a GARCH-style model incorporating the Yang and Zhang (2000) estimator using the open, high, low, and close data
-source: VIX from Quandl, calculated in VRP.ipynb

12.Implied Correlation (IC)

-the average equity options-implied correlation, CBOE S&P 500 Implied Correlation Index
-source: Quandl

13.Baltic Dry Index (BDI)

-three month change in the BDI
-source: Bloomberg

14.New Orders/Shipments (NOS)

-log of the originally reported new orders divided by the original shipments
-source: http://www-bcf.usc.edu/~tuzel/

15.Consumer Price Index (CPI)

-the change in CPI over the last twelve months  
-source: Quandl

16.Ratio of Stock Price to Commodity Price (PCR)

-log of the ratio between SPY and GSCI  
-Source: Bloomberg

17.Moving Average (MA)

-0/1 signal based on SMA(20)-SMA(200)
-source: alculated in SPX_tech.xlsx

18.Principal Component of Technical Indicators (PCAtech)

-the first principal component of a set of technical indicators(Neely et al,2014)  
-source: calculated in SPX_tech.xlsx and calculateFirstPC.ipynb

19.Oil Price Shocks (OIL)

-the log of the current front oil futures price (CL1) minus the log of the fourth futures price (CL4) with a three month lag    
-source: Bloomberg

20.Short Interest (SI)

-the sum of all shares short on the NYSE divided by the average daily trading volume over the past 30 days    
-source: Quandl


Normal text **bold** then *italic*.
Escape \* \` \< \_ \# \\ & more.

1. Order list
- Unorder list ( - or + )

code: `a === a`

> blockquote

URL: [Edditoria][1] | image: ![2][]

[1]: https://edditoria.blogspot.com
[2]: https://avatars0.githubusercontent.com/u/2234073?v=3&s=40

<!-- please comment -->

# Enjoy! :)

[[https://github.com/niyuan17/Linear_Forecasting/blob/master/correlation_of_predictors.jpg|alt=octocat]]


![Alt text](correlation_of_predictors.jpg)


