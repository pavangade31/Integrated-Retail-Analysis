# Integrated Retail Analytics for Store Optimization

## Objective
To develop an end-to-end analytics and machine learning solution for forecasting weekly demand, detecting anomalies, and generating actionable business insights for retail store optimization.

## Dataset Description
- Sales Data: Weekly sales records across multiple retail stores.
- Features: Store ID, Department, Date, Weekly Sales, Temperature, Fuel Price, CPI, Holiday Flags, Promotions.
- Additional Data: Seasonal, holiday, and external factors integrated for demand forecasting and anomaly detection.

## Methods & Techniques
- Data Preprocessing: Handling missing values, outlier treatment, feature encoding, scaling.
- Feature Engineering: Lag features, rolling means, holiday indicators, weather-based variables.
- Exploratory Data Analysis (EDA): Trend analysis, seasonality detection, correlation heatmaps.
- Forecasting Models: ARIMA, SARIMA for time series forecasting.
- Machine Learning Models: XGBoost for predictive modeling.
- Anomaly Detection: STL decomposition, Statistical Process Control (SPC), Isolation Forest.
- Visualization Tools: Tableau, Power BI, Python (Matplotlib, Seaborn, Plotly).

## Tasks Performed
- Built ETL pipeline for sales data integration
- Conducted EDA to identify trends, patterns, and anomalies
- Created 90+ features for forecasting and segmentation
- Benchmarked forecasting models and selected SARIMA (Rel.MAE: 2.48%, RMSE: 3.71%)
- Implemented hybrid anomaly detection (STL + SPC + ML)
- Developed interactive dashboards for KPI tracking, store segmentation, and performance analysis

## Key Visualizations
- Weekly sales trends and seasonality plots
- Correlation heatmaps and feature importance charts
- Anomaly detection visualizations (time-series plots)
- Store performance dashboards (Top/Bottom stores)
- Forecast vs Actual comparison plots

## Results
- SARIMA model outperformed ARIMA, reducing relative MAE by 27%
- Anomaly detection framework flagged 1.44% anomalous series, improving inventory planning
- Developed interactive dashboards for decision-makers to monitor KPIs and optimize store strategies

## Business Recommendations
- Adjust inventory planning for seasonal peaks to avoid stockouts or overstock
- Monitor anomalies in real-time for proactive supply chain adjustments
- Leverage customer segmentation insights for targeted promotions and loyalty programs
- Adopt predictive analytics dashboards for strategic decision-making across stores

## Tech Stack
- Programming: Python (Pandas, NumPy, Scikit-learn, Statsmodels)
- Visualization: Tableau, Power BI, Plotly, Seaborn
- Forecasting: SARIMA, ARIMA
- Machine Learning: XGBoost, Isolation Forest
- Database: SQLite
- Others: ETL pipelines, KPI dashboards
