# Time-Series-Analysis-of-Ethereum-ETH-USDT-Mar--ket-Projections-using-ARIMA
ETH Market Analysis ARIMA

📈 Time Series Analysis of Ethereum (ETH/USDT) Price using ARIMA
This project performs time series analysis and forecasting on historical Ethereum (ETH/USDT) price data using the ARIMA (Autoregressive Integrated Moving Average) model. The goal is to analyze price trends, test stationarity, and generate accurate 30-day price forecasts to gain insights into Ethereum's market dynamics.

🔍 Project Highlights
📅 Data Source: Cleaned historical ETH/USDT data (daily resolution)

📊 EDA: Price trends, volatility patterns, and volume analysis

🧪 Stationarity Testing: ADF tests and differencing

🧠 ARIMA Modeling: Optimal (p,d,q) selection using ACF/PACF plots

📉 Model Evaluation: RMSE & MAPE error metrics

🔮 Forecasting: 30-day future price prediction with confidence intervals

📷 Visualizations: Forecast plots, residuals, and model diagnostics

🧰 Tools & Libraries
pandas, numpy – data manipulation

matplotlib, seaborn – visualizations

statsmodels – ARIMA modeling & diagnostics

scikit-learn – evaluation metrics

📁 Structure
kotlin
Copy
Edit
├── data/
│   └── ethusdt_price.csv
├── notebooks/
│   └── eth_arima_analysis.ipynb
├── results/
│   └── forecast_plot.png
├── README.md
└── requirements.txt
🚀 Getting Started
Clone the repo

bash
Copy
Edit
git clone https://github.com/waleedshah0/Time-Series-Analysis-of-Ethereum-ETH-USDT-Mar--ket-Projections-using-ARIMA.git
cd eth-arima-forecast
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook
Open eth_arima_analysis.ipynb and follow along.

📌 Insights
While ARIMA provides a simple yet powerful framework for time series forecasting, it has limitations in modeling high volatility and non-linear behavior often seen in crypto markets. However, with proper preprocessing and parameter tuning, it can deliver reliable short-term forecasts.

