# Avocado-Price-Forecasting-Using-Machine-Learning-Time-Series


📌Project Overview

This project aims to analyze avocado sales data over time to understand demand patterns and pricing behavior across different regions, and to build a model that forecasts product prices for the next four weeks.

📂 Dataset Information

The dataset(Demand_Sale.csv): includes detailed order-level information such as date, product size, product type (Conventional or Organic), quantity sold, region, and price per case.



🧹 Data Preparation & Cleaning

Handling missing values

Converting data types

Standardizing category labels (CNV vs cnv)

Removing invalid or duplicate entries

🔎 Exploratory Data Analysis (EDA)

Sales trends over time

Regional differences in demand

Performance of different product sizes

Price behavior and volatility

Relationships between price and quantity

⚙️ Feature Engineering

Time-based features: week, month, year extracted from the date

Lag features: previous week’s price or quantity

Rolling averages: average price or quantity over past 2–4 weeks

Encoding categorical variables: convert regions, product type, and sizes into numeric

Finally, time-series forecasting models were built separately for each product size using algorithms such as Random Forest, XGBoost, and SARIMAX, while ensuring no data leakage. The goal is to generate reliable forecasts that support better pricing and demand management decisions.
