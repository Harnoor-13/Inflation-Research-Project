# Inflation-Research-Project
This consists of my journey in modelling the predictory inflation for the upcoming months in india using dl



Project Summary

This project focuses on time-series forecasting of India's Consumer Price Index (CPI). A comparative analysis was conducted between several machine learning and deep learning models to identify the most effective architecture for this task. The core of the analysis involves building, training, and evaluating models on historical CPI data to predict future inflation trends.



Dataset

The study utilizes historical monthly CPI data for India, contained within the `Indian_CPI_Data.csv` file. The data was preprocessed by normalizing values using a `MinMaxScaler` and structuring it into sequences suitable for time-series modeling.

Jupyter Notebooks

* **`for_2_months_.ipynb`**: Implements and evaluates CNN, LSTM, and hybrid CNN-LSTM models for a 2-month CPI forecasting horizon.
* **`3_months_nbeats_xgboost_cnn_lstm.ipynb`**: Provides a comparative analysis of N-BEATS, XGBoost, CNN, LSTM, and CNN-LSTM models for a 3-month forecast, identifying the best-performing model.
* **`2025_3_months_lstm_cnn.ipynb`**: Applies the developed CNN, LSTM, and hybrid models to generate a specific 3-month inflation forecast for the year 2025.



Future Aim

The future direction of this project involves enhancing forecast accuracy by incorporating relevant exogenous variables, such as GDP, national interest rates, and key commodity prices. Further research will also explore more advanced architectures, including **Transformer-based models** and **Temporal Fusion Transformers (TFTs)**, to better capture complex long-range dependencies within the economic data.
