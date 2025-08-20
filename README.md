# Walmart Sales Forecasting

Predict future sales across Walmart stores using time series analysis.

---

## Project Overview
This project focuses on forecasting Walmart store sales to optimize inventory, plan promotions, and improve operational efficiency. The main goal is to identify patterns in historical sales data and generate accurate predictions for future sales.

---

## Objective
- Predict future sales for Walmart stores across different regions and departments.
- Identify trends and seasonal patterns in sales.
- Support data-driven decision-making for inventory and promotions.

---

## Dataset
The dataset is sourced from **Kaggle**:  
[Walmart Sales Dataset](https://www.kaggle.com/datasets)  

It contains historical sales data, holiday information, and store details.

---

## Approach
1. **Data Collection & Preprocessing:**  
   - Handle missing values and outliers.  
   - Normalize and clean data.  
2. **Exploratory Data Analysis (EDA):**  
   - Visualize trends, seasonality, and correlations.  
3. **Modeling:**  
   - Apply SARIMA and other time series models.  
   - Tune parameters using ACF/PACF plots and AIC/BIC criteria.  
4. **Evaluation:**  
   - Metrics: MSE, RMSE, MAE, and MAPE.  
   - Achieved ~2–4% MAPE per store.  
5. **Forecasting:**  
   - Generate short-term and long-term sales predictions.

---

## Key Features
- Seasonal and trend analysis using SARIMA.
- Visualization of sales patterns and trends.
- Forecasting performance evaluation with multiple metrics.
- Insights for inventory optimization and promotion planning.

---

## Impact
- Helped manage stock better and reduce overstock/stockouts.  
- Increased sales with smarter promotions.  
- Improved operational efficiency across stores.  
- Achieved ~2–4% MAPE for each store, ensuring reliable forecasts.

---

## Tools & Libraries
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Plotly  
- **Time Series & Stats:** Statsmodels, SciPy  
- **Evaluation:** Scikit-learn metrics (MSE, RMSE, MAE, MAPE)  

---
