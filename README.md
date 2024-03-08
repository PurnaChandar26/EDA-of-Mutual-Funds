# EDA of Mutual Funds
 
## Introduction 
The Exploratory Data Analysis (EDA) of mutual funds using a dataset that provides various attributes of mutual funds. The dataset includes information such as scheme name, minimum investment requirements, expense ratio, fund size, fund age, fund manager details, and performance metrics over different time periods. In this analysis, I explored and analyzed the dataset to gain insights into the mutual fund industry. 

## ***Please explore the 'EDA Findings' PDF in the files above to discover the insightful results, conclusions, and findings uncovered through my EDA efforts.***
## Dataset Overview 
Let's begin by understanding the structure of the dataset:
   
- **scheme_name:** The name of the mutual fund scheme.
- **min_sip:** The minimum amount required for a Systematic Investment Plan (SIP) investment in the fund.
- **min_lumpsum:** The minimum amount required for a lump sum investment in the fund.
- **expense_ratio:** The expense ratio of the fund.
- **fund_size_cr:** The size of the fund in crore (10 million) units.
- **fund_age_yr:** The age of the fund in years.
- **fund_manager:** The name of the fund manager.
- **sortino:** The Sortino ratio of the fund, which measures the risk-adjusted return of the fund.
- **alpha:** The alpha of the fund, which measures the excess return of the fund compared to its benchmark.
- **sd:** The standard deviation of the fund's returns.
- **beta:** The beta of the fund, which measures the sensitivity of the fund's returns to the market.
- **sharpe:** The Sharpe ratio of the fund, which measures the risk-adjusted return of the fund relative to a risk-free asset.
- **risk_level:** The risk level of the fund, categorized as Very High, High, Moderately High, Moderately Low, or Low.
- **amc_name:** The name of the asset management company that manages the fund.
- **rating:** The rating of the fund on a scale of 1 to 5, with 1 being the lowest and 5 being the highest.
- **category:** The category of the fund, such as Equity, Debt, or Hybrid.
- **sub_category:** The sub-category of the fund, such as Large Cap, Small Cap, Floater Mutual Funds, etc.
- **returns_1yr:** The return of the fund in the past year.
- **returns_3yr:** The return of the fund in the past 3 years.
- **returns_5yr:** The return of the fund in the past 5 years.
 

## Key EDA Findings:


### 1. Analysis on Risk Level
Examined the distribution of mutual funds based on their risk levels.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/93854552-8b1b-4760-92f8-8d7ceb55b171)

### 2. Analysis on Asset Management Companies (AMCs)
Provided insights into the distribution of mutual funds among different asset management companies.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/f1f650ca-e357-4d3d-a0db-84041930af19)

### 3. Analysis on Fund Categories and Sub-Categories
Explored the distribution of mutual funds across different categories and sub-categories.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/94d449da-b32b-4409-b2d6-cf7483a73684)

### 4. Analysis of Standard Deviation (SD)
Examined the standard deviation of fund returns to assess their volatility.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/9ecbed66-d117-4ee4-bf96-4e86de4bcd86)


### 5. Top 5 Fund Managers in Each Category by Average 5-Year Returns
Categorized funds by type (Equity, Debt, Hybrid) and listed the top 5 fund managers in each category based on the average 5-year returns of their funds.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/500c429e-076b-45b9-a3fe-e62357fa541e)


### 6. Top 10 Fund Managers with the Highest Assets Under Management (AUM)
Ranked the top 10 fund managers based on the total assets under management across their schemes.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/03bc1ee8-9176-4809-bacd-cfa85b5f2a50)

### 7. Expense Ratio Variation Across Different Fund Size Groups and Categories
Examined how the expense ratio varied across different fund size groups and categories.

![image](https://github.com/PurnaChandar26/EDA-of-Mutual-Funds/assets/97793147/ca207ffc-3190-4996-a2c6-6641b6ead908)

### 8. SIP and Lump Sum Investment Requirements by Category
Analyzed and compared the minimum SIP and lump sum investment requirements across different fund categories.

### 9. Analysis of Alpha
Analyzed the alpha values of mutual funds to assess their performance relative to benchmarks.

### 10. Analysis of Beta
Analyzed the beta values of mutual funds to understand their sensitivity to market movements.

### 11. Analysis on Sharpe Ratio
Evaluated the Sharpe ratio of mutual funds to gauge their risk-adjusted returns.

### 12. Analysis on Sortino Ratio
Examined the Sortino ratio of mutual funds to assess their risk-adjusted returns with a focus on downside risk.

## Disclaimer
Mutual fund investments are subject to market risk. This notebook is for educational purposes only, and it is essential to consult with a financial advisor or expert before making any investment decisions in mutual funds. The information provided in this analysis is based on historical data and should not be considered as financial advice or a recommendation for investment. 
