# 📊 Trader Performance vs Market Sentiment Analysis

## 🧠 Objective
Analyze how market sentiment (Fear/Greed) affects trader behavior and performance using Hyperliquid trading data.

---

## 📂 Dataset
- Bitcoin Market Sentiment (Fear/Greed Index)
- Historical Trader Data (Hyperliquid)

---

## ⚙️ Methodology

1. Data Cleaning
- Converted timestamps to date format
- Handled missing values
- Merged datasets on date

2. Feature Engineering
- Daily PnL
- Trade frequency
- Average trade size
- Long/Short ratio

3. Analysis
- Compared behavior across Fear, Greed, Neutral
- Used boxplots and tables for visualization

---

## 📊 Key Insights

1. Trading activity is highest during Greed periods.
2. Traders take larger risks during Fear periods.
3. Fear markets show higher volatility and extreme PnL outcomes.
4. Traders show slight short bias even during Greed.

---

## 🚀 Strategy Recommendations

1. During Fear markets, reduce position size and manage risk strictly.
2. During Greed markets, increase participation but use profit-booking strategies.

---

## 🛠️ Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repo
2. Install requirements:
   pip install pandas matplotlib seaborn
3. Run notebook.ipynb