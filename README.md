
# 📊 Bitcoin Market Sentiment vs Trader Performance Analysis

## 📌 Overview

This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **Hyperliquid trader performance**. The objective is to understand how market sentiment influences trading behavior, profitability, and trading activity using interactive Power BI dashboards.

---

# 📂 Dashboard 1 – Market Sentiment Overview

<img width="1920" height="1080" alt="Screenshot (160)" src="https://github.com/user-attachments/assets/12a39857-1e9e-4e40-8537-3486746a472c" />


### Dashboard Title

**Bitcoin Market Sentiment vs Trader Performance Analysis**

### KPI Cards

| KPI              | Description                                                             |
| ---------------- | ----------------------------------------------------------------------- |
| **Total PnL**    | Displays the total profit and loss generated from all completed trades. |
| **Total Trades** | Shows the total number of executed trades.                              |
| **Win Rate**     | Represents the ratio of profitable trades to total trades.              |
| **Average PnL**  | Displays the average profit or loss earned per trade.                   |
| **Total Fees**   | Shows the total transaction fees paid by traders.                       |

---

### Visualizations

### 1️⃣ Market Sentiment Distribution (Pie Chart)

**Purpose**

Shows the distribution of Bitcoin market sentiment categories such as:

* Fear
* Extreme Fear
* Greed
* Extreme Greed
* Neutral

**Insight**

Helps understand how frequently each market sentiment occurred during the analysis period.

### 2️⃣ Total PnL by Market Sentiment (Column Chart)

**Purpose**

Compares total trader profits across different market sentiment categories.

**Insight**

Identifies which sentiment produced the highest or lowest trading profitability.


### 3️⃣ Buy vs Sell Trade Analysis (Column Chart)

**Purpose**

Compares Buy and Sell trading activity under each market sentiment.

**Insight**

Shows how trader behavior changes during Fear and Greed market conditions.


### 4️⃣ Daily Trading Activity (Line Chart)

**Purpose**

Displays daily trading performance over time.

**Insight**

Highlights trading trends and periods with increased market activity.



# 📂 Dashboard 2 – Trader Performance Analysis
<img width="1920" height="1080" alt="Screenshot (159)" src="https://github.com/user-attachments/assets/631e384b-e1fb-4a6b-a9c3-4f7225165fa9" />

### Visualizations

### 1️⃣ Trading Volume vs Closed PnL by Market Sentiment (Scatter Plot)

**Purpose**

Analyzes the relationship between trade size (USD) and realized profit/loss.

**Insight**

Helps identify whether larger trades generate higher profits under different market sentiments.



### 2️⃣ Total Closed PnL by Cryptocurrency (Horizontal Bar Chart)

**Purpose**

Displays the profitability of different cryptocurrencies.

**Insight**

Identifies the coins that generated the highest trading profits.


### 3️⃣ Top Trader Accounts by Total Closed PnL (Horizontal Bar Chart)

**Purpose**

Ranks trader accounts based on realized profits.

**Insight**

Highlights the best-performing trader accounts in the dataset.


### 4️⃣ Winning vs Losing Trades Across Market Sentiments (100% Stacked Column Chart)

**Purpose**

Compares winning and losing trades under different market sentiment conditions.

**Insight**

Evaluates whether market sentiment impacts trading success rates.



### 5️⃣ Cryptocurrency Performance Matrix (Matrix Table)

**Purpose**

Summarizes cryptocurrency performance across different market sentiment categories.

**Insight**

Provides a detailed comparison of trading performance for each cryptocurrency.



### 6️⃣ Interactive Trading Filters (Hierarchy Slicer)

**Purpose**

Allows users to filter the dashboard by:

* Date
* Coin
* Trader Account
* Market Sentiment

**Insight**

Enables dynamic exploration of trader performance.



# 📊 Key Insights

* Trading performance changes significantly across different market sentiment conditions.
* Fear and Extreme Fear periods exhibit greater market volatility.
* Greed periods generally have higher trading activity.
* Some cryptocurrencies consistently outperform others regardless of market sentiment.
* A small number of trader accounts contribute a significant portion of total profits.
* Larger trade sizes do not always result in higher profitability, emphasizing the importance of effective risk management.



# 🛠 Tools Used

* **Power BI** – Data visualization and dashboard creation
* **Python (Pandas)** – Data preprocessing and cleaning
* **GitHub** – Version control and project documentation



# 📁 Project Structure

```text
Bitcoin-Market-Sentiment-Analysis/
│
├── data/
│   ├── fear_greed_index.csv
│   └── historical_data.csv
│
├── dashboards/
│   └── Bitcoin_Market_Analysis.pbix
│
├── screenshots/
│   ├── dashboard1.png
│   └── dashboard2.png
│
├── README.md
│
└── requirements.txt
```


# 🚀 Conclusion

This project demonstrates how **Bitcoin market sentiment** can be combined with **historical trader performance** to uncover meaningful trading patterns. The interactive Power BI dashboards provide valuable insights into profitability, trading behavior, and market dynamics, enabling users to make more informed, data-driven trading decisions.
