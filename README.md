# ◈ FinSight AI — Financial Intelligence Platform

<div align="center">

## AI-Powered Financial Intelligence for Smarter Investment Decisions

Explore global stock markets manually or generate a personalized mutual fund investment path using structured risk analysis, goal-based planning, quantitative metrics, and interactive financial analytics.

[**🚀 Live Demo**](https://financialintelligenceplatform-ixnjnesparf33mfmccwhy4.streamlit.app/) | [**💻 GitHub Repository**](https://github.com/shreya975/Financial_Intelligence_Platform)

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge&logo=streamlit)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-blueviolet?style=for-the-badge&logo=plotly)
![Pandas](https://img.shields.io/badge/Pandas-Analytics-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Computing-blue?style=for-the-badge&logo=numpy)
![Finance](https://img.shields.io/badge/Financial%20Analytics-Intelligence-green?style=for-the-badge)

</div>

---

# 🌍 Project Overview

Financial decisions often require users to combine market data, historical performance, risk analysis, investment goals, and portfolio considerations across different tools.

**FinSight AI** brings these capabilities together into a single interactive financial intelligence platform.

The platform provides two complementary investment journeys:

- 📈 **Stock Intelligence** — Explore global stocks, markets, trends, performance, and financial metrics.
- 🤖 **Mutual Fund Intelligence** — Assess investor risk, define goals, generate asset allocation, filter funds, and rank recommendations.

The platform is built with **Python, Streamlit, Pandas, NumPy and Plotly**, with an interactive financial dashboard.

> **The goal is not simply to display financial data — but to turn it into structured, understandable investment intelligence.**

---

# 🚀 Key Features

## 📈 Stock Intelligence

Explore global markets through an interactive analytics dashboard.

### Market Analytics

- Dynamic stock and country filtering
- Historical price analysis
- OHLCV market data
- Daily return analysis
- 20-day and 50-day moving averages
- Rolling volatility analysis
- Stock performance comparison
- Volume analysis
- Country-level market statistics

### 📊 Interactive Visualizations

- Price charts
- Candlestick analysis
- Performance comparisons
- Volume analytics
- Trend analysis
- Market overview charts
- Country-level comparisons

## 🤖 Mutual Fund Recommendation Engine

A structured quantitative engine designed to convert investor preferences into a personalized mutual fund strategy.

### 🧠 Risk Profiling

The engine evaluates investor preferences using structured behavioral and financial questions, including:

- Reaction to investment losses
- Investment priorities
- Previous investment experience
- Income stability
- Comfort with market fluctuations
- Financial preferences

### 🎯 Goal-Based Planning

The recommendation flow considers:

- Investment objective
- Investment horizon
- Investment capacity
- Risk tolerance
- Desired financial outcome

### 💰 Portfolio Construction

The engine follows a structured pipeline:

```text
Investor Inputs
      ↓
Risk Assessment
      ↓
Risk Score
      ↓
Goal + Investment Horizon
      ↓
Asset Allocation
      ↓
Fund Filtering
      ↓
Risk Compatibility
      ↓
Fund Quality Evaluation
      ↓
Portfolio Ranking
      ↓
Personalized Recommendation
```

The recommendation engine follows a **rule-based quantitative approach rather than relying on a machine-learning prediction model**.

### 📐 Quantitative Metrics

- Standard Deviation
- Beta
- Sharpe Ratio
- Sortino Ratio
- 3-Year Returns
- Expense Ratio
- Fund Quality Score
- Risk Score

---

# 🧠 Business Questions Answered

FinSight AI helps users explore questions such as:

### Stock Intelligence

- Which stocks are performing strongly?
- How has a stock performed historically?
- Which markets have higher trading activity?
- How volatile is a stock?
- How do stocks compare across countries?
- What are the recent price and volume trends?

### Mutual Fund Intelligence

- What is my investment risk profile?
- How should my portfolio be allocated?
- Which funds match my risk level?
- How does investment horizon affect the strategy?
- Which funds rank higher based on quantitative metrics?
- What could my potential wealth trajectory look like?

---

# 🔄 How It Works

## 01 — Choose Your Path

Choose between:

**📈 Manual Mode**

Explore stocks, markets, countries, trends, and analytics.

**🤖 Automation Mode**

Provide your financial goals, investment horizon, capacity, and risk preferences.

## 02 — Analyze

The platform processes the selected inputs and presents:

- Market analytics
- Financial metrics
- Interactive visualizations
- Risk assessment
- Portfolio allocation
- Fund analysis
- Quantitative rankings

## 03 — Understand

Convert the results into a structured view of:

**Market → Risk → Goal → Allocation → Investment Options**

---

# 📊 Platform Capabilities

| Capability | Description |
|---|---|
| 📈 Stock Intelligence | Global stock market exploration |
| 🌍 Global Analytics | Country-level market analysis |
| 📊 Interactive Charts | Plotly-powered financial visualizations |
| 🧠 Risk Profiling | Structured investor risk assessment |
| 🎯 Goal-Based Planning | Investment planning based on goals |
| 💰 Fund Recommendations | Quantitative mutual fund ranking |
| 📐 Financial Metrics | Risk and performance measurements |
| 📊 Wealth Projection | Potential investment outcome visualization |
| 🎨 Interactive UI | Financial dashboard experience |

---

# 📂 Project Structure

```text
Financial_Intelligence_Platform/
│
├── app.py
│
├── mf_engine.py
│
├── final_data.csv
│
├── mutual_funds.csv
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Data & Analytics

## Stock Market Data

The Stock Intelligence module works with historical market data containing fields such as:

| Attribute | Description |
|---|---|
| Date | Trading date |
| Open | Opening price |
| High | Highest price |
| Low | Lowest price |
| Close | Closing price |
| Volume | Trading volume |
| Stock Name | Company identifier |
| Country | Market/country |

The application derives additional analytical fields including **Daily Return, MA20, MA50 and Volatility** during data processing.

## Mutual Fund Data

The recommendation module evaluates mutual funds using quantitative characteristics such as:

- Risk
- Returns
- Standard deviation
- Beta
- Sharpe ratio
- Sortino ratio
- Expense ratio
- Fund quality

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Core application development |
| **Streamlit** | Interactive web application |
| **Pandas** | Data processing and analysis |
| **NumPy** | Numerical computation |
| **Plotly** | Interactive financial visualizations |
| **CSS3** | Custom dashboard styling |

---

# 🎨 Dashboard Experience

FinSight AI focuses on providing an interactive financial dashboard experience featuring:

- 🌑 Dark-themed interface
- ✨ Modern dashboard components
- 📊 Interactive KPI components
- 📈 Financial charts
- 🎯 Structured recommendation journey
- 🔄 Navigation between different modules

---

# ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/shreya975/Financial_Intelligence_Platform.git
```

### 2. Move into the project directory

```bash
cd Financial_Intelligence_Platform
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python -m streamlit run app.py
```

### 5. Open in browser

```text
http://localhost:8501
```

---

# 🔬 Recommendation Engine

The mutual fund module follows a transparent quantitative pipeline instead of relying on a black-box ML prediction model.

The recommendation process considers:

- Investor risk profile
- Investment objectives
- Investment horizon
- Asset allocation
- Risk compatibility
- Fund quality
- Category-relative returns
- Sharpe and Sortino ratios
- Expense ratio

The final portfolio is generated by combining these quantitative factors into a structured recommendation process.

---

# ⚠️ Model Limitations

FinSight AI is an **educational and quantitative research platform**, not a registered financial advisory service.

Generated recommendations and projections are based on available data and model assumptions. They do not guarantee future performance and should not be considered professional financial advice.

---

# 🔥 Future Improvements

Potential extensions include:

- 📡 Real-time market data
- 📰 Financial news sentiment analysis
- 🤖 ML-based forecasting models
- 📉 Advanced risk metrics
- 📊 Portfolio optimization
- 🔔 Price and portfolio alerts
- 🧠 Explainable recommendation scoring
- 📱 Mobile-focused interface
- 🔐 User portfolio tracking
- ☁️ Persistent cloud-based portfolios

---

# 👩‍💻 About Me

## **Shreya Mahajan**

Aspiring Data Scientist | Python Developer | Financial Analytics Enthusiast

Interested in building data-driven products across:

- 📊 Data Analytics
- 💰 Financial Intelligence
- 🤖 Machine Learning
- 🐍 Python Development
- 📈 Interactive Dashboards
- 🧠 AI-Powered Applications

**GitHub:** [shreya975](https://github.com/shreya975)

---

# ⭐ Support

If you find **FinSight AI** interesting:

⭐ Star the repository  
🍴 Fork the project  
💬 Share feedback  
🐛 Report issues  
💡 Suggest improvements

---

<div align="center">

### ◈ FinSight AI

**Explore the market. Understand the data. Build a smarter investment path.**

Built with Python • Streamlit • Pandas • NumPy • Plotly

[🚀 Live Demo](https://financialintelligenceplatform-ixnjnesparf33mfmccwhy4.streamlit.app/) · [💻 GitHub](https://github.com/shreya975/Financial_Intelligence_Platform)

</div>
