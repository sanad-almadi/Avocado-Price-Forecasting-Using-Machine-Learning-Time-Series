# Avocado-Price-Forecasting-Using-Machine-Learning-Time-Series


#📌Project Overview
This project aims to analyze avocado sales data over time to understand demand patterns and pricing behavior across different regions, and to build a model that forecasts product prices for the next four weeks.

📂 Dataset Information
The dataset includes detailed order-level information such as date, product size, product type (Conventional or Organic), quantity sold, region, and price per case.




A complete data science pipeline was applied, starting with data cleaning, handling missing values, and standardizing data types, followed by feature engineering by extracting time-based features (week, month, year), creating lag features, and computing rolling averages to capture temporal changes.


🔎(EDA) was conducted to identify:

Sales trends over time.

Regional differences in demand.

Performance of different product sizes.

Price behavior and volatility.

Relationships between price and quantity.


Finally, time-series forecasting models were built separately for each product size using algorithms such as Random Forest, XGBoost, and SARIMAX, while ensuring no data leakage. The goal is to generate reliable forecasts that support better pricing and demand management decisions.
