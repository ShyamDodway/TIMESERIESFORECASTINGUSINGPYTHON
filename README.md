# Time Series Forecasting of Energy Consumption 🔋📈

## 📊 Project Description
This project uses hourly electricity consumption data from the PJM Energy Market to forecast future energy demand using time series modeling.

## 🛠 Tools Used
- Python
- Pandas, Numpy
- Statsmodels (SARIMA)
- Matplotlib, Seaborn
- Google Colab

## 📁 Dataset
- Source: [PJM Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)

## ⚙️ Process Overview
1. **Data Preprocessing**: Resampled hourly data into daily means.
2. **EDA**: Visualized trends, seasonality, and stationarity.
3. **Modeling**: Applied SARIMA to capture seasonality and trend.
4. **Evaluation**: Used MAE and MAPE for accuracy on a 30-day forecast.

## 📉 Results
- **MAPE**: ~2.6%
- **MAE**: ~503
- The model forecasted daily energy demand with high accuracy.

## 💡 Business Impact
This model helps in energy planning and demand management, reducing costs and ensuring grid reliability.

## 📎 Notebook
Check out the Colab notebook [here](pjme_energy_forecasting.ipynb).

