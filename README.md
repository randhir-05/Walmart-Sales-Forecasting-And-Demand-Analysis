# Walmart Sales Forecasting And Demand Analysis
<img width="1258" height="400" alt="Screenshot 2024-12-24 at 11 52 53 PM" src="https://github.com/user-attachments/assets/d7ea28a9-89c8-4219-bc35-ee9f7672539c" />

# Project Overview

This project focuses on forecasting Walmart's weekly sales and analyzing demand patterns to derive actionable business insights. Leveraging both time-series and machine learning models, the project evaluates factors influencing sales, such as holidays, temperature, fuel price, CPI, and unemployment rates. The ultimate goal is to provide reliable forecasts to support inventory planning and promotional strategies.

# Key Features

Data Exploration & Preprocessing: Cleaned, transformed, and visualized data from the Walmart dataset to identify key trends and patterns.

Exploratory Data Analysis (EDA):

Seasonal trends in weekly sales.

Impact of holidays and economic indicators like CPI and unemployment.

Time-Series Analysis:

Seasonal decomposition to identify trend, seasonality, and residuals.

Stationarity tests (ADF, KPSS) to validate the data’s suitability for ARIMA modeling.

# Modeling & Forecasting:

ARIMA: Selected as the best model based on superior accuracy metrics.

XGBoost Regressor: Evaluated for comparison; excels in variance explanation but lags in forecasting precision.

# Model Evaluation:

Metrics: MAE, RMSE, MAPE, and R².

Visual comparisons of predicted vs. actual sales.

Results

ARIMA Model:

MAE: 57,100.53

RMSE: 81,633.93

MAPE: 5.64%

Rationale: Selected due to its lower error metrics and strong handling of seasonality and trend.

XGBoost Regressor:

MAE: 74,373.25

RMSE: 138,920.67

MAPE: 7.59%

R²: 0.940

Rationale: While XGBoost explains variance effectively, it underperforms ARIMA in forecasting accuracy.

# Tech Stack

Programming Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn, XGBoost

Tools: Jupyter Notebook, Kaggle Environment

# Insights and Business Impact

Seasonal Trends: High sales during December, April, June, and July.

Holiday Effects: Non-holiday weeks consistently outperform holiday weeks.

Temperature Influence: Sales peak between 20°F to 60°F, with dense sales between 60°F to 80°F.

Economic Indicators: Unemployment and CPI significantly impact sales patterns.

# Business Recommendations:

Increase inventory during high-sales months (December, April, June, July).

Implement targeted promotions during non-holiday periods to boost demand.

Strategically manage inventory in areas with fluctuating CPI and unemployment rates.

Feel free to reach out for collaborations or feedback!
