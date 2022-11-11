# Finance Project: Global Diversification 

### Motivation: Investigate whether investing globally would lead to lower risks and higher long-term returns

---------

### Project Preview: 

#### 1. Programming Language: Python 

#### 2. Data extracted from Yahoo Finance 
- Link: https://finance.yahoo.com/

#### 3. Details of the 3 chosen ETFs for analysis: 
- SPDR S&P 500 ETF (track S&P 500 index) --> United States
- iShares Core MSCI Europe ETF (tracks the MSCI Europe IMI) --> Europe
- iShares Asia 50 ETF (tracks S&P 500 Asia index) --> Asia

#### 4. Initial Hypothesis: Investing globally WILL lead to a DECREASE in investment risks and an INCREASE in returns

---------

### Project Details (look into ipny file): 

#### 1. Descriptive Statistics and Graphs
- Daily mean & Annual Return
- Standard Deviation

#### 2. Correlation
- Correlation Matrix & Heatmap
- Spearman Rank Correlation Test

#### 3. Portfolio Comparison (Equal vs Diversified) 
- Hypothesis Test (t-test & f-test) with 5% significance level

#### 4. Economic Significance 
- Returns & Risks (std) on each ETF
- Portfolio Returns & Risks (std) & Sharpe ratio

#### 5. CAPM Model
- Regression Analysis 

#### 6. 4-Factor Model 
- SMB --> Small Cap / Large Cap Stock
- HML --> Value / Growth Stock 
- RF ---> Risk Free Rate 
- Mom --> Momentum Stock (Yes or No) 

#### 7. Portfolio Sort 
- Sorts trading days according to trading volumes of all ETFs and examines their return differences between high volume days and low volume days
- Separated into quintiles (5), with 0 being the lowest trading volume, and 4 being the highest

#### 8. Limitations
- Kurtosis (might underestimate / overestimate due to the inclusion of extreme outcomes)
