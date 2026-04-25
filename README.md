# ACC102 Track 2: Apple Inc. (AAPL) Stock Performance Analysis
## Project Overview
This project is a Python-based data analysis product for ACC102 Mini Assignment. It retrieves monthly stock data for Apple Inc. (AAPL) and U.S. market benchmark data from the WRDS CRSP database, conducts data cleaning, return calculation, risk analysis, and visualization. The goal is to analyze AAPL’s return, volatility, correlation with the market, and performance compared to the U.S. stock market from 2021 to 2024.

## Data Source
- Individual Stock Data: CRSP Monthly Stock File (crsp.msf)
- Market Benchmark: CRSP Value-Weighted Market Index (crsp.msi, vwretd)
- Time Period: 2021-01-01 to 2024-12-31
- Data Platform: WRDS (Wharton Research Data Services)

## Tools & Libraries
- Python 3
- pandas: Data loading, merging, cleaning, and calculation
- matplotlib & seaborn: Data visualization
- wrds: Access WRDS database
- os: File and folder management

## Analytical Workflow
1. Retrieve AAPL monthly stock data and market index data
2. Data cleaning, missing value removal, and column renaming
3. Calculate monthly returns, cumulative returns, excess returns, and rolling volatility
4. Estimate market beta via regression scatter plot
5. Generate 6 professional charts and auto-save high-resolution images
6. Summarize key financial insights on risk and return

## Key Visualizations
1. Cumulative Performance vs. U.S. Market
2. Return Correlation & Beta Coefficient Scatter Plot
3. 6-Month Rolling Annualized Volatility Comparison
4. Cumulative Excess Return over Market
5. Monthly Return Distribution Histogram
6. Annual Return Comparison Bar Chart

## Main Insights
- AAPL achieved higher cumulative returns than the overall U.S. market during 2021–2024.
- AAPL has a beta greater than 1, meaning it is more volatile than the market.
- AAPL’s rolling volatility is consistently higher than the market benchmark.
- AAPL delivered positive excess returns over most of the sample period.
- Annual return comparison shows strong outperformance in most years.

## How to Run
1. Ensure WRDS account access and required libraries installed
2. Open the Jupyter Notebook file
3. Modify the ticker symbol if needed
4. Run all cells sequentially to reproduce analysis and charts
5. Generated charts are automatically saved in the 'acc102_plots' folder

## Acknowledgement
This project is completed as an individual assignment for ACC102 at Xi’an Jiaot-Liverpool University. All data is used for educational purposes only.
- Limited to 3 companies; can include more stocks
- Uses simple risk metrics; can add CAPM or regression
- Data frequency is daily; can test monthly data
