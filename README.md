# 📊 Sales Forecasting System  
AI-powered Time Series Forecasting with Python & Streamlit  

This project analyzes historical retail sales data and predicts future sales using classical and machine-learning forecasting models.  
A modern Streamlit dashboard visualizes forecast trends, performance metrics, and underlying data insights.

---

## 🚀 Features

### ✅ Data Processing & Cleaning  
- Handles missing timestamps  
- Converts raw date columns into usable time-series format  
- Aggregates daily → monthly sales  
- Removes nulls & inconsistencies  

### ✅ Exploratory Data Analysis (EDA)  
- Trend Visualization  
- Seasonal Decomposition  
- Autocorrelation & PACF plots  

### ✅ Feature Engineering  
- Lag features (1,2,3,6,12)  
- Rolling means  
- Time-based features (month, year, quarter)  

### ✅ Forecasting Models  
| Model | Description |
|-------|-------------|
| **SARIMAX** | Classical time-series forecasting |
| **XGBoost Regression** | ML-based forecasting using engineered features |
| **Prophet (optional)** | Additive forecasting model |

<img width="1032" height="431" alt="image" src="https://github.com/user-attachments/assets/a002bcd5-4722-42ea-9b23-f2af7ef38b1d" />

<img width="646" height="523" alt="image" src="https://github.com/user-attachments/assets/d2d6b788-58c0-4206-a02c-036e8dea2613" />


### ✅ Streamlit Dashboard  
- KPI Cards (Latest Actual, Forecast, Error %)  
- Interactive Line Chart (Actual vs Predicted)  
- Clean Forecast Table  
- Dark modern UI  

***Streamlit Output***

<img width="1013" height="899" alt="image" src="https://github.com/user-attachments/assets/8e0a71a7-97b4-45fb-8261-bb740a0adacd" />

https://karissa-wistful-uncolourably.ngrok-free.dev/
