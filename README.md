# Data Analytics Portfolio

## The Mission

Every dataset tells a story, a hidden pattern, a suspicious price drop, a revenue curve waiting to be forecast. This repository is where I go looking for those stories. It is a hands on collection of applied data analytics work spanning audit analytics, regression modeling, and time series forecasting, built with Python (pandas, statsmodels, matplotlib) and RStudio.

Each notebook below is a standalone investigation: raw data in, a clear analytical question, and a defensible answer out, the same workflow used in real audit, and financial analytics roles.

## The Expeditions

### Audit Analytics
Digging through transactional sales and inventory data to flag anomalies auditors actually care about, including inconsistent pricing across transactions, below cost sales, and potential inventory misstatements. Uses groupby, multi table merges, and threshold based flagging to surface risk at scale (millions of rows, not a toy dataset).

### Regression Analysis
Building and evaluating OLS regression models (via statsmodels) to explain revenue using operational drivers like production volume and weather driven demand (cooling and heating degree days). Includes model comparison using MAPE (Mean Absolute Percentage Error) to determine which model actually predicts best, not just which one looks good on paper.

### Dummy Variables
Extending regression models with categorical (dummy) variables and interaction terms to capture structural shifts in behavior, for example how the relationship between production and revenue changes during winter months versus the rest of the year.

### Time Series Forecasting
Using time itself as the independent variable to forecast future values, trained on historical quarterly revenue, tested against real held out data, with confidence intervals around each forecast rather than a single point guess.

## Tools of the Trade

Python, pandas, NumPy, statsmodels, matplotlib, RStudio, Statistical Modeling, Regression Diagnostics, Time Series Forecasting

## How This Repo Is Organized

data_analytics_portfolio/
audit_analytics/
regression_analysis/
dummy_variables/
time_series_forecasting/
README.md

Each notebook runs and displays its results directly on GitHub. Outputs, tables, and charts are saved in place, so you can see the full analysis without needing to execute anything yourself.

## Why This Exists

This portfolio is a running record of applied analytics work, proof that I can take a raw dataset, ask the right question, and back up the answer with a model that holds up under testing. More projects get added as the investigation continues.
