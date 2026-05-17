# 📈 Sales Demand Forecasting — Time Series Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Prophet](https://img.shields.io/badge/Prophet-Time%20Series-purple) ![Status](https://img.shields.io/badge/Status-Complete-green)

## 📌 Overview
Time series forecasting model using **Facebook Prophet** to predict future sales demand for next 90 days. Built on Superstore Sales dataset (9,800 rows). Applicable to supply chain planning and inventory management in retail and telecom sectors.

## 🎯 Objective
- Analyze historical sales trends (2015–2018)
- Identify yearly and weekly seasonality patterns
- Forecast next 90 days of sales demand
- Provide actionable insights for business planning

## 📊 Dataset
- **Source:** Kaggle — Superstore Sales Dataset
- **Size:** 9,800 rows
- **Period:** 2015–2018

## 🛠️ Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming |
| Prophet | Time series forecasting |
| Pandas | Data processing |
| Matplotlib | Visualization |
| Jupyter / VS Code | Development |

## 🔍 Methodology
1. Date parsing & data cleaning
2. Monthly sales aggregation
3. EDA — Category & Regional trends
4. Prophet model training (yearly + weekly seasonality)
5. 90-day future forecast with confidence intervals
6. Seasonality component analysis

## 📈 Key Results
- **Forecast Period:** 90 days
- **Seasonality:** Strong yearly pattern detected
- **Best Category:** Technology
- **Best Region:** West ($725K+)

## 📊 Visualizations
1. Sales by Category & Region (bar charts)
2. Monthly Sales Trend 2015-2018
3. Category-wise Monthly Trend
4. 90-Day Forecast with Confidence Interval
5. Seasonality Components (trend + weekly + yearly)

## 📁 Project Structure
```
demand-forecasting/
├── demand_forecasting.ipynb
├── train.csv
├── plot1_sales_overview.png
├── plot2_monthly_trend.png
├── plot3_category_trend.png
├── plot4_forecast.png
├── plot5_components.png
└── README.md
```

## 💡 Business Relevance
- **Telecom (Telenor):** Network load forecasting, customer demand prediction
- **FMCG (Nestlé):** Product demand planning, supply chain optimization
- **Retail:** Inventory management, seasonal planning

## 👤 Author
**Muhammad Laeeq Ur Rehman**
- GitHub: [github.com/data00077](https://github.com/data00077)
- LinkedIn: [linkedin.com/in/muhammadlaeeq-ur-rehman-094457374](https://linkedin.com/in/muhammadlaeeq-ur-rehman-094457374)
