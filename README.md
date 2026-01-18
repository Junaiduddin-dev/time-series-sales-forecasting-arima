# Time Series Sales Forecasting with ARIMA

## 📌 Project Overview
This project focuses on forecasting monthly sales for the next quarter (3 months) using the ARIMA (AutoRegressive Integrated Moving Average) model in Python.  
The workflow includes time series visualization, stationarity testing, ARIMA model fitting, forecasting with confidence intervals, and model evaluation.

---

## 🎯 Goal
Forecast the next 3 months of sales using ARIMA and measure the performance using accuracy metrics.

---

## 🛠 Technologies Used
- Jupyter Notebook  
- Python  
- pandas  
- matplotlib  
- statsmodels  
- pmdarima  
- scikit-learn  

---

## ✅ Steps Performed
1. Created/loaded monthly sales dataset
2. Visualized sales trend and checked seasonality
3. Performed ADF (Augmented Dickey-Fuller) test for stationarity
4. Applied differencing to make the data stationary (if needed)
5. Used `auto_arima()` to find the best ARIMA parameters
6. Trained the ARIMA model on training data
7. Forecasted next 3 months with confidence intervals
8. Evaluated performance using:
   - MAE (Mean Absolute Error)
   - MAPE (Mean Absolute Percentage Error)

---

## 📊 Output
- Sales trend plot
- Differenced series plot
- Forecast plot with confidence interval
- Accuracy metrics (MAE and MAPE)

---

## 📁 Files in this Repository
- `Time_Series_ARIMA_Forecasting.ipynb` → complete notebook with code and outputs  
- `README.md` → project documentation  

---

## ▶️ How to Run
1. Open the notebook in Jupyter Notebook or Google Colab
2. Install dependencies:
   ```bash
   pip install pandas matplotlib statsmodels pmdarima scikit-learn
