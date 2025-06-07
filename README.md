

# 📈 Mastercard Stock Market Analysis & Forecasting

This project analyzes and forecasts Mastercard’s stock performance using Python. It includes historical trend analysis, visual exploration, and ARIMA-based time series forecasting.

---

## 📂 Dataset

The dataset `Mastercard_stock_history.csv` includes:

- Date  
- Open  
- High  
- Low  
- Close  
- Adj Close  
- Volume

---

## 🎯 Objectives

- Load and clean Mastercard stock market data  
- Visualize trends across time  
- Train and evaluate an ARIMA model  
- Forecast future stock prices  
- Extract insights for financial decision-making  

---

## 🚀 Features

- 📊 Time-series trend analysis (Open, High, Low, Close prices)  
- 📉 Subplots to compare opening vs closing prices  
- 🔮 Short-term price prediction using ARIMA  
- 📐 Math explanation of ARIMA  
- 📚 Clean and ready-to-use dataset  

---

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/mastercard-stock-analysis.git
cd mastercard-stock-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook Mastercard_Stock_Market_Kaggle.ipynb
```

---

## 📊 Exploratory Data Analysis

📉 Price Trend Over Time  
Visualized closing prices across time using a line plot. This shows how the stock performed throughout the dataset timeline.

📊 Open, Close, High, Low Comparison Over Time  
A multi-line chart was used to compare Open, Close, High, and Low prices to understand volatility and trading behavior.

📉 Subplots for Opening vs Closing Price  
Used two vertically stacked plots to show how the stock opened and closed each day, highlighting gaps or consistent pattern.

---

## 🔮 Forecasting with ARIMA

The ARIMA model (AutoRegressive Integrated Moving Average) was used to forecast Mastercard's closing price for the next 30 days.

### Model Equation

$$
Y_t = c + \phi_1 Y_{t-1} + \phi_2 Y_{t-2} + \dots + \phi_p Y_{t-p} + \theta_1 \varepsilon_{t-1} + \dots + \theta_q \varepsilon_{t-q} + \varepsilon_t
$$

Where:  
- \\( Y_t \\): Predicted value  
- \\( \phi \\): AR coefficients  
- \\( \theta \\): MA coefficients  
- \\( \varepsilon \\): White noise error  

---

## 📌 Key Takeaways

- Mastercard has a strong long-term upward trend  
- Clean dataset with no missing values  
- ARIMA is useful for short-term forecasting  

---

## 🔧 Recommendations

- Try deep learning (e.g., LSTM) for longer-term forecasting  
- Add economic indicators (e.g., interest rate, CPI)  
- Include technical signals like MACD and RSI  

---

## 🗂️ Project Structure

```
📦 Mastercard-Stock-Analysis
 ┣ 📄 Mastercard_stock_history.csv
 ┣ 📄 Mastercard_Stock_Market_Kaggle.ipynb
 ┗ 📄 README.md
```

---

## 👩‍💻 Author

**Durga Pravallika Kuchipudi**  
M.S. in Applied Data Science  
🔗 [LinkedIn](https://www.linkedin.com/in/durgapk/)  
📧 dpkuchipiu@gmail.com

---

## 📄 License

This project is licensed under the MIT License.
```
