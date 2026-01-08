# 📈 Stock Market Prediction and Forecasting using Stacked LSTM

## 📌 Project Overview

This project focuses on predicting and forecasting stock market prices using a **Stacked Long Short-Term Memory (LSTM)** deep learning model. LSTM networks are well-suited for time-series data as they can capture long-term dependencies, making them ideal for stock price prediction.

The model is trained on historical stock price data to learn patterns and trends, and then used to predict future stock prices.

---

## 🎯 Objectives

* Analyze historical stock market data
* Perform data preprocessing and feature scaling
* Build a **Stacked LSTM** model for time-series forecasting
* Predict future stock prices
* Visualize actual vs predicted stock prices

---

## 🧠 Technology Stack

* **Programming Language:** Python
* **Libraries & Frameworks:**

  * NumPy
  * Pandas
  * Matplotlib
  * Scikit-learn
  * TensorFlow / Keras

---

## 📂 Project Structure

```
Stock_Market_Prediction_And_Forecasting_using_Stacked_LSTM.ipynb
README.md
```

---

## 🗂 Dataset

* Historical stock market price data (CSV format)
* Features typically used:

  * Date
  * Open price
  * High price
  * Low price
  * Close price
  * Volume

> Note: The dataset is preprocessed and scaled before training the model.

---

## ⚙️ Workflow

1. **Data Collection** – Load historical stock price data
2. **Data Preprocessing** – Handle missing values, scaling, and formatting
3. **Train-Test Split** – Prepare data for model training
4. **Model Building** – Implement a stacked LSTM architecture
5. **Model Training** – Train the model using historical data
6. **Prediction** – Forecast future stock prices
7. **Visualization** – Plot actual vs predicted prices

---

## 🧪 Model Architecture

* Input Layer
* Multiple **LSTM layers (Stacked LSTM)**
* Dense output layer

This architecture helps the model capture complex patterns in time-series data.

---

## 📊 Results

* The model successfully predicts stock price trends
* Visualization helps compare predicted values with actual prices
* Performance depends on data quality and training parameters

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory
3. Open the Jupyter Notebook

   ```bash
   jupyter notebook Stock_Market_Prediction_And_Forecasting_using_Stacked_LSTM.ipynb
   ```
4. Run all cells sequentially

---

## 📈 Future Enhancements

* Use multiple stock datasets
* Add technical indicators (RSI, MACD, Moving Averages)
* Hyperparameter tuning
* Deploy the model using Streamlit or Flask

---

## 📜 Disclaimer

This project is for **educational purposes only** and should not be used for real financial trading decisions.

---

## 👤 Author

**Prajwal Mavkar**

---

⭐ If you found this project helpful, don’t forget to star the repository!
