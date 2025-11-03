# 📈 Stock Price Forecast App

This Streamlit web application predicts future stock prices using **Linear Regression** based on historical data fetched from **Yahoo Finance**.  
It provides an interactive dashboard for users to analyze trends, visualize predictions, and forecast the next day’s stock price.

---

## 🚀 Features

- 📊 Fetches real-time stock data from Yahoo Finance  
- 📅 Adjustable analysis period (30–365 days)  
- 🤖 Applies **Linear Regression** for trend prediction  
- 📈 Visualizes actual vs predicted prices  
- 📉 Displays key metrics: RMSE and R² Score  
- 🔮 Forecasts next day’s predicted price  
- 💾 Expandable table for recent data view  

---

## 🧠 Technologies Used

- [Streamlit](https://streamlit.io/)
- [Yahoo Finance API (yfinance)](https://pypi.org/project/yfinance/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)

---

## 🧰 Installation and Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/stock-price-forecast.git
   cd stock-price-forecast
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run streamlit_TLR.py
   ```

4. **Open in browser**
   The app will open automatically, or visit [http://localhost:8501](http://localhost:8501).

---

## ⚙️ How It Works

1. User inputs a stock ticker (e.g., AAPL, TSLA, MSFT)  
2. Selects a time window (number of days to analyze)  
3. The app:
   - Fetches the stock’s historical data
   - Trains a Linear Regression model
   - Displays:
     - Actual vs Predicted prices
     - Model metrics (RMSE, R²)
     - Next-day price forecast

---

## 📷 Example Output

**Dashboard Preview:**
- Metrics for RMSE, R², Current Price  
- Interactive line chart comparing predicted vs actual prices  
- Forecast for the next trading day  

---

## 🧩 File Structure

```
📁 stock-price-forecast/
│
├── streamlit_TLR.py       # Main Streamlit app
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## 🧑‍💻 Author

**Bhagyashree S**  
_Data Science Enthusiast | AI & Machine Learning Developer_  
📬 [LinkedIn](https://github.com/Iambhagya-DSA) | ✉️ [Email](bhagyashree2019s@gmail.com)

---

## 🪪 License

This project is licensed under the **MIT License** – feel free to use and modify it.

---

## 💡 Future Enhancements

- Integrate LSTM or ARIMA for advanced forecasting  
- Add sentiment analysis based on financial news  
- Include multi-stock comparison dashboard  
- Deploy via Streamlit Cloud or Hugging Face Spaces  
