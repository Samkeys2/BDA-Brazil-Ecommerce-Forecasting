# Brazil E-commerce Order Forecasting Project

This Business Data Analytics project analyzes Brazilian e-commerce transactional data to develop short-term order forecasting models that support supply chain planning and operational decision-making.

The project applies exploratory data analysis, feature engineering, and time-series forecasting techniques to evaluate order behavior, delivery performance, and short-term forecasting accuracy within the Brazilian e-commerce sector.

## Models Evaluated
- Naive Benchmark
- ARIMA
- Random Forest

## Methodology
Data cleaning and preprocessing
Exploratory data analysis (EDA)
Lag and rolling-window feature engineering
Walk-forward validation using a 1-day-ahead forecasting horizon
Model evaluation using MAE, RMSE, and MAPE metrics

## Key Findings
Recent order activity showed strong short-term persistence.
The Naive model performed strongly for short-term forecasting tasks.
Random Forest achieved lower RMSE values and captured demand variability more effectively.
Weekly order patterns and regional delivery differences were identified across Brazilian states.
Higher-demand states generally experienced faster delivery performance.

## Repository Contents
Brazil_Ecommerce_Forecasting_nootbook.ipynb
data/
README.md

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Statsmodels
