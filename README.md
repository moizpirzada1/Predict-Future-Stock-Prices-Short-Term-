# Predict-Future-Stock-Prices-Short-Term-
# 📈 Task 2: Predict Future Stock Prices (Short-Term)

## 🧠 Objective
Use historical stock market data to predict the **next day’s closing price** using regression modeling.

---

## 📂 Dataset
- Source: [Yahoo Finance](https://finance.yahoo.com)
- Fetched using the `yfinance` Python library
- Example stock: **TSLAInc. (TSLA)**  
  You can change to others like `AAPL`, `GOOGL`, `AMZN`, etc.

---

## ⚙️ Technologies Used
- Python
- `yfinance` (for data retrieval)
- `pandas`, `numpy` (data manipulation)
- `scikit-learn` (Linear Regression & Random Forest)
- `matplotlib` (for visualization)

---

## 🔄 Workflow

1. **Fetch historical stock data** (Open, High, Low, Volume, Close)
2. **Create features**: Use current day's `Open`, `High`, `Low`, `Volume`  
   as input to predict **next day's `Close`** price.
3. **Split data** into training and test sets
4. **Train models**:
   - Linear Regression
   - Random Forest Regressor
5. **Evaluate** using MAE and RMSE
6. **Visualize** actual vs predicted prices

---

## 💻 How to Run

1. Install dependencies:
   ```bash
   pip install yfinance scikit-learn pandas matplotlib
