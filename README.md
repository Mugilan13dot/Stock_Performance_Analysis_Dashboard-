# 📊 Stock Performance Analysis Dashboard (Apple, Microsoft, Netflix, Google)

This project analyzes and compares the recent 3-month stock performance of four major tech companies: **Apple (AAPL)**, **Microsoft (MSFT)**, **Netflix (NFLX)**, and **Google (GOOGL)** using **Tableau**. As a Business Analyst, the goal was to extract actionable insights on stock performance, volatility, and market behavior.

---
📍 View the dashboard here: [Stocks Analysis](/Stocks_Analysis.twbx/)

![StocksAnalysis](/Assets/Stock_Market_Summary.png) 

## 🧠 Project Objective

📈 **Identify investment opportunities** by analyzing stock price trends, growth, volatility, and trading volume over the past 3 months using interactive dashboards.

---

## 🛠️ Tools Used

- **Tableau** – for data visualization and interactive dashboards  
- **CSV Dataset** – historical daily stock data (Open, Close, Adj Close, Volume)

---

## 📁 Data Overview

The dataset includes:
- `Date`
- `Ticker` (AAPL, MSFT, NFLX, GOOGL)
- `Open`, `Close`, `Adj Close`, `Volume`
- Derived fields: `Daily Return`, `Total Return (%)`

---

## 📊 The Dashboard Includes

| Visualization | Purpose | Business insights |
|---------------|---------|-------------------|
| 📈 **Line Chart** – Adjusted Close over Time | Compare daily price trends | “Apple and Microsoft showed consistent upward trends, while Netflix had more volatile swings. Google remained flat overall.” |
| 📊 **Bar Chart** – % Total Return | Identify best/worst performer | “Microsoft returned +12.3%, the highest among the fo ur. Netflix returned only +2.1%, while Google slightly declined during this period. This makes Microsoft the top short-term performer.” |
| 📦 **Box Plot** – Daily Return Volatility | Evaluate risk profile | Netflix (NFLX) might show high variation in returns = higher risk, Apple (AAPL) may have a tighter box = lower risk |
| 🔊 **Area Chart** – Trading Volume Over Time | Spot market activity spikes | 📈 Netflix volume spike → Could indicate a major announcement, 📰 Google trading surge → Possibly due to earnings or AI product news |
| 🧾 **KPI Cards** | Show Best Performer, Most Volatile Stock, Highest Volume Day | Microsoft outperformed all other stocks over the last 3 months, showing consistent upward price movement and strong investor confidence, Netflix experienced frequent price swings, indicating high trading risk but also potentSudden trading surge indicates potential market-moving event or investor reaction to news/announcements.ial for short-term gains. |

---
## 🧠 Business Analyst Wrap-Up Summary

-“This dashboard reveals that **Microsoft (MSFT)** delivered the best 3-month return at **+12.3%**, making it the top performer. **Netflix (NFLX)** was the most volatile, offering high-risk trading opportunities. Meanwhile, **Google (GOOGL)** had the highest trading volume day—likely due to news events. These insights help stakeholders assess growth, risk, and market behavior for investment planning.”


## 📌 Key Business Insights

- ✅ **Best Performer**: Microsoft (MSFT) with **+12.3%** return
- ⚠️ **Most Volatile**: Netflix (NFLX), indicating higher trading risk
- 🔊 **Highest Trading Volume**: Google (GOOGL) mid-March — likely event/news-driven
- 📉 Apple (AAPL) showed steady and low-risk performance, ideal for long-term investors

---

## 📎 Sample Visuals

![AdjCloseOverTime](\Assets\AdjClose_OverTime.png)  
![Total_Return_comparison](\Assets\Total_Return_comparison.png) 
![Trading_Volume_Overtime](\Assets\Trading_Volume_Overtime.png)

---
## 🧾 Business Use Cases

- 💼 Investor sentiment and performance benchmarking
- 📈 Volatility assessment for risk management
- 🔍 Trading volume spike detection for news/event correlation
- 📊 Portfolio diversification insights

---

## 🧰 How to Reproduce

1. Download the dataset: `stocks.csv`
2. Open Tableau and connect to the file
3. Create calculated fields:
   - `Daily Return`
   - `Total Return`
4. Build charts and arrange into dashboard
5. Add KPI cards and filters

---

## 💡 What I Learned

- Creating aggregate vs non-aggregate calculations in Tableau
- Using table calculations like `LOOKUP()` and `WINDOW_MIN/MAX()`
- Designing dashboards with business storytelling in mind
- Presenting insights for executive-level decision-making

---

## 📬 Contact

**Author**: Mugilan R.  
📧 mugilanr396@gmail.com


---

