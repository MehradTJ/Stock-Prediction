
# 📈 Stock Price Prediction Using Time Series Analysis and Neural Networks

## 📝 Overview
This project focuses on stock price prediction using historical data and various machine learning techniques. The workflow includes data acquisition, preprocessing, visualization, and the implementation of multiple neural network models to predict stock prices. The study explores different architectures, including LSTM, GRU, CNN, and MLP, and evaluates their performance on both normalized and non-normalized data.

## ⚙️ Features
- **Data Acquisition**: Downloads and processes stock data from Yahoo Finance.
- **Data Preprocessing**: Cleans missing values and applies normalization.
- **Exploratory Data Analysis (EDA)**: Includes statistical analysis and visualization.
- **Time Series Forecasting**: Implements various neural network architectures.
- **Performance Evaluation**: Compares models using metrics such as MSE and MAE.
- **Naïve Baseline**: Implements a simple Naïve Forecasting model for comparison.

## 🗂️ Project Structure
```
├── stock_price_prediction.ipynb   
├── README.md                       
├── requirements.txt                
```

## 📦 Installation
To run the project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

### 1️⃣ Run Data Acquisition & Preprocessing
- The notebook downloads and processes stock data from Yahoo Finance.
- Cleans missing values and prepares time series data for modeling.

### 2️⃣ Visualize Stock Data
- Generates candlestick charts for price trends.
- Plots histograms to analyze stock return distributions.

### 3️⃣ Train Neural Network Models
- Trains **LSTM**, **GRU**, **BiLSTM**, **MLP**, **CNN**, and **ConvLSTM** on selected stocks.
- Evaluates models on both normalized and non-normalized data.

### 4️⃣ Evaluate & Compare Predictions
- Uses **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)** for assessment.
- Implements **Naïve Forecasting** as a baseline model.

## 🧠 Models Implemented
- **Long Short-Term Memory (LSTM)**
- **Gated Recurrent Unit (GRU)**
- **Bidirectional LSTM (BiLSTM)**
- **Multilayer Perceptron (MLP)**
- **Convolutional Neural Network (CNN)**
- **Convolutional LSTM (ConvLSTM)**

## 📊 Results & Findings
- **LSTM**, **GRU**, **BiLSTM**, and **CNN** demonstrated strong predictive accuracy.
- Data normalization significantly improved model performance.
- The **Naïve Forecasting** model provided a simple but reasonable baseline.

## 🔮 Future Work
- Experimenting with **hybrid models** (e.g., combining CNN with LSTM).
- Extending prediction horizons beyond a single day.
- Incorporating additional financial indicators to improve forecasting accuracy.

## 👨‍💻 Contributors
- **Mehrad Tajik**

## 📜 License
This project is licensed under the **MIT License**. See LICENSE for details.
