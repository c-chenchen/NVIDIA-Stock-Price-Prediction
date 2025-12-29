# 📈 Stock Price Prediction Using LSTM
This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices using historical market data. The model is trained on past price movements and evaluated on its ability to forecast future values.
---
## 📌 Overview
Stock prices exhibit sequential and temporal patterns, making them suitable for time-series models such as LSTMs.
This project demonstrates how deep learning can be applied to financial data for predictive analysis.
---
## 🛠 Technologies Used
- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- yFinance

---
## 📂 Project Structure
```
├── stock_price_prediction.ipynb
├── README.md
```
---
## ⚙️ Methodology

### 1. Data Collection
Historical stock price data is downloaded using the yfinance API.

### 2. Preprocessing

- Select closing prices
- Normalize data using standard scaling
- Create fixed-length input sequences

### 3. Model Architecture

- LSTM layers for sequential learning
- Fully connected output layer

### 4. Training

- Loss function: Mean Squared Error (MSE)
- Optimizer: Adam
- Training over multiple epochs

### 5. Evaluation

- Predictions compared with true values
- Performance measured using RMSE
- Visualization of predictions and errors

---
## 📊 Results
The model captures general price trends but struggles with sudden market fluctuations.
While the predictions appear smooth, the model mainly learns past patterns rather than true future movements.

---
## 🚀 How to Run
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
jupyter notebook stock_price_prediction.ipynb
```
---
## 📌 Notes
This project is intended for educational purposes and should not be used for financial decision-making.










