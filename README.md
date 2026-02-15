# Sensex-project-repo
This repository contains Sensex market data used for data analysis and machine learning projects related to stock price prediction.


# 📈 SENSEX Data Collection & Feature Engineering Pipeline

This project builds a complete data pipeline for downloading, cleaning, and engineering technical indicators on historical stock market data of the **BSE SENSEX** using Python.

The processed dataset is prepared for Machine Learning and Time Series Forecasting tasks.

## 🚀 Project Overview

This project performs:

* 📥 Historical data download from Yahoo Finance
* 🧹 Data cleaning and preprocessing
* 📊 Technical indicator generation (SMA, RSI)
* 💾 Exporting clean dataset for ML model training

The final dataset is saved as:

```
sensex_data_clean.csv
```

## 🛠 Tech Stack

* Python
* pandas
* numpy
* yfinance
* Technical Indicators (SMA, RSI)


## 📂 Project Structure

```
📁 sensex-ml-project
│
├── sensex_pipeline.py
├── sensex_data_clean.csv
├── README.md
```


## 📊 Features Engineered

The following technical indicators are added:

| Feature | Description                    |
| ------- | ------------------------------ |
| SMA_50  | 50-day Simple Moving Average   |
| SMA_200 | 200-day Simple Moving Average  |
| RSI     | 14-day Relative Strength Index |

These indicators are widely used in financial time-series modeling and stock prediction systems.


## 📥 Data Source

Data is fetched using the `yfinance` library from Yahoo Finance.

Ticker Used:

```
^BSESN
```

Index:
**BSE SENSEX**

Time Period:

```
2010-01-01 to 2026-02-07
```


## ⚙️ How to Run

### 1️⃣ Install Dependencies

```bash
pip install yfinance pandas numpy
```

### 2️⃣ Run Script

```bash
python sensex_pipeline.py
```

### 3️⃣ Output

A cleaned dataset will be generated:

```
sensex_data_clean.csv
```


## 🧠 Use Cases

This dataset can be used for:

* Stock price prediction
* Time series forecasting
* Machine learning regression models
* LSTM-based deep learning models
* Financial trend analysis


## 📌 Future Improvements

* Add EMA (Exponential Moving Average)
* Add MACD indicator
* Add Bollinger Bands
* Add target column for next-day prediction
* Train ML models (Linear Regression, Random Forest, XGBoost, LSTM)
* Deploy as web app using Streamlit


## 📈 Sample Workflow

```
Download Data → Clean Data → Add Indicators → Save CSV → Train ML Model
```

## 👨‍💻 Author

Aditya Sharma
BTech CSE (AI/ML Enthusiast)



Tell me what level you want — basic, intermediate, or advanced 🚀
