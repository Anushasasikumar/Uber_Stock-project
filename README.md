## Predicting Uber's Stock Price Using Deep Learning Techniques

## 📌 Project Overview
Developed a time series forecasting model to predict Uber’s stock prices using deep learning techniques. Implemented its architectures to analyze historical data and evaluate model performance for accurate predictions.

## Dataset Description
This dataset contains historical stock price data for Uber Technologies Inc. (UBER), spanning from May 10, 2019, to February 5, 2025. It includes daily trading information with the attributes of **Date**, **Open**, **High**, **Low**, **Close**, **Adj Close**, **Volume**.

Dataset Link - https://www.kaggle.com/datasets/varpit94/uber-stock-data

## 🧠 Key Objectives
- Perform exploratory data analysis on Uber stock data.
- Visualize stock price trends.
- Analyze volume fluctuations and volatility.
- Apply predictive models for stock forecasting.

## 🛠️ Tools & Technologies
- **Programming Language**: Python  
- **Libraries Used**: Pandas, NumPy, Matplotlib, Seaborn 
- **Algorithms Applied**:
  - Long Short Term Memory (LSTM)
  - Gated Recurrent Unit (GRU)
  - Recurrent Neural Network (RNN)
  - Bi- Directional LSTM

## 📊 Analysis Performed
  -  Converted Date column to datetime and set it as index.
  -  Checked for null values and handled them appropriately.
  -  Generated plots for:
      -  Daily Close price trend
      -  Volume vs. price relationship
      -  Rolling mean to identify long-term trends
  -  Compared Open vs Close prices using multi-line plots.
  -  Created heatmaps and pairplots for correlation analysis

## Conclusion
In this project, we conducted a comprehensive analysis of Uber's historical stock data using Python and various data visualization techniques. By transforming and cleaning the dataset, we were able to generate clear insights into how Uber’s stock has behaved over time.
Uber’s stock exhibits notable fluctuations in both price and volume, with certain patterns indicating possible market behavior trends.Visualization of rolling averages helped highlight long-term trends and reduce the noise in daily price movements.Strong correlations were observed between Open, Close, and Adj Close prices, suggesting consistent price behavior within trading sessions.
