# Time Series Forecasting of Energy Consumption 

##  Project Description
This project uses hourly electricity consumption data from the PJM Energy Market to forecast future energy demand using time series modeling.

##  Tools Used
- Python
- Pandas, NumPy
- Statsmodels (SARIMA)
- Matplotlib, Seaborn
- Google Colab / Jupyter Notebook

##  Dataset
- Source: [PJM Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)
- Data contains hourly electricity usage in megawatts from 2002 to 2018.
- Resampled hourly data to daily averages for smoother trends.

##  Process Overview
1. **Data Preprocessing**: Resampled hourly data into daily means; handled missing data.
2. **Exploratory Data Analysis (EDA)**: Visualized trends, seasonality, and patterns.
3. **Modeling**: Built a SARIMA model to capture trend and seasonality in the time series.
4. **Evaluation**: Forecasted the next 30 days and evaluated using MAE and MAPE metrics.

##  Results
- **Mean Absolute Error (MAE):** _e.g., 503_
- **Mean Absolute Percentage Error (MAPE):** _e.g., 2.6%_
- The SARIMA model successfully forecasted daily energy demand with high accuracy.

##  Business Impact
This forecasting model can help energy providers optimize resource planning, reduce costs, and avoid outages by anticipating demand fluctuations.

##  How to Run
- Clone the repository:
  ```bash
  git clone https://github.com/yourusername/energy-forecasting.git
