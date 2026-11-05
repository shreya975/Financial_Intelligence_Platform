# ◈ FinSight AI – Financial Intelligence Platform

An interactive financial intelligence platform that brings global stock market analytics and personalized mutual fund recommendations together in one place. Built with Python and Streamlit, FinSight AI combines financial data analysis, quantitative risk assessment, goal-based investment planning, and interactive visualizations to make financial insights easier to understand.

<p align="center">
  <a href="https://financialintelligenceplatform-ixnjnesparf33mfmccwhy4.streamlit.app/">
    <strong>🚀 Live Demo</strong>
  </a>
  &nbsp; | &nbsp;
  <a href="https://github.com/shreya975/Financial_Intelligence_Platform">
    <strong>💻 GitHub Repository</strong>
  </a>
</p>

---

## 📌 Overview

FinSight AI is designed to simplify financial analysis by combining two important areas of investing: stock market intelligence and mutual fund portfolio planning.

Instead of switching between multiple platforms, users can explore stock market performance, analyze historical trends, understand investment risks, and generate personalized mutual fund strategies through a single interactive application.

The platform is divided into three main sections:

- **FinSight Home:** A unified landing page for navigating the platform.
- **Stock Intelligence:** An interactive dashboard for exploring global stock market data and performance.
- **Mutual Fund Intelligence:** A quantitative recommendation engine that evaluates investor risk profiles and generates goal-oriented mutual fund portfolios.

## ✨ Key Features

### 📈 1. Global Stock Intelligence

- Explore 300+ stocks across 20 countries.
- Filter stocks based on country and stock name.
- Analyze historical stock price movements.
- Interactive date-range selection.
- Track opening, closing, high and low prices.
- Calculate daily returns and rolling volatility.
- Analyze 50-day moving averages.
- Compare stock performance through interactive visualizations.
- View market-level statistics and stock performance metrics.

### 💰 2. Mutual Fund Recommendation Engine

- Personalized investor risk assessment through a questionnaire.
- Five investor risk categories:
  - Very Conservative
  - Conservative
  - Moderate
  - Aggressive
  - Very Aggressive
- Goal-based investment planning.
- Investment horizon-based asset allocation.
- Equity, Debt and Hybrid fund classification.
- Quantitative mutual fund ranking.
- Fund quality and risk compatibility assessment.
- Portfolio construction based on investment capacity.

### 📊 3. Portfolio Analytics & Wealth Planning

- Personalized monthly SIP allocation.
- Mutual fund selection based on quantitative scores.
- Risk-adjusted portfolio recommendations.
- Portfolio quality evaluation.
- SIP and lump-sum investment calculations.
- Future wealth projections.
- Conservative, expected and optimistic return scenarios.
- Target-based SIP calculation.
- Interactive financial charts and visualizations.

## 🧠 How the Recommendation Engine Works

The mutual fund recommendation engine follows a structured quantitative approach:

1. **Investor Profiling:** Evaluates investor preferences, financial stability, investment experience and risk tolerance.
2. **Goal Analysis:** Considers financial goals and investment duration.
3. **Asset Allocation:** Determines an appropriate allocation across Equity, Debt and Hybrid categories.
4. **Risk Adjustment:** Modifies the allocation based on the investor's risk profile.
5. **Fund Ranking:** Evaluates funds using risk compatibility, fund quality, historical returns, Sharpe ratio, Sortino ratio and expense ratio.
6. **Portfolio Construction:** Selects suitable funds and calculates the monthly SIP distribution.
7. **Wealth Projection:** Estimates potential investment growth over the selected investment horizon.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Frontend & Dashboard | Streamlit |
| Data Processing | Pandas, NumPy |
| Data Visualization | Plotly, Matplotlib, Seaborn |
| Financial Data | yfinance |
| Recommendation Engine | Python-based quantitative scoring and ranking |
| Data Storage | CSV datasets |

## 🏗️ Project Structure

```text
Financial_Intelligence_Platform/
│
├── app.py
│   └── Main Streamlit application
│       ├── Home Page
│       ├── Stock Intelligence
│       └── Mutual Fund Intelligence
│
├── mf_engine.py
│   └── Mutual Fund Recommendation Engine
│       ├── Investor Risk Profiling
│       ├── Goal-Based Allocation
│       ├── Fund Ranking
│       ├── Portfolio Construction
│       └── Wealth Projection
│
├── MF_India_AI_Risk_Engine.csv
│   └── Mutual Fund Risk and Analytics Dataset
│
├── final_data.csv
│   └── Financial Data
│
├── requirements.txt
│   └── Project Dependencies
│
└── README.md
```

## ⚙️ Installation & Setup

Follow these steps to run FinSight AI locally.

**1. Clone the repository**

```bash
git clone https://github.com/shreya975/Financial_Intelligence_Platform.git

cd Financial_Intelligence_Platform
```

**2. Create a virtual environment**

```bash
python -m venv venv
```

**3. Activate the environment**

Windows:

```bash
venv\Scripts\activate
```

macOS / Linux:

```bash
source venv/bin/activate
```

**4. Install dependencies**

```bash
pip install -r requirements.txt
```

**5. Run the application**

```bash
streamlit run app.py
```

**6. Open in your browser**

```text
http://localhost:8501
```

## 📊 What Makes This Project Interesting?

FinSight AI focuses on bringing financial analytics and investment planning into a single application.

Some important aspects of the implementation include:

- Combining global stock analytics and mutual fund intelligence in one Streamlit application.
- Building a weighted quantitative investor risk-scoring mechanism.
- Implementing goal-based asset allocation with risk adjustments.
- Developing a multi-factor fund ranking algorithm.
- Calculating SIP and lump-sum investment projections.
- Using interactive visualizations to make financial data easier to interpret.

## 🔮 Future Enhancements

- Integration of additional real-time financial data sources.
- Advanced machine learning-based stock forecasting.
- Portfolio optimization using modern portfolio theory.
- News-based financial sentiment analysis.
- Automated portfolio monitoring and alerts.
- More advanced personalized investment insights.

## ⚠️ Disclaimer

FinSight AI is an educational financial analytics and investment planning project. Portfolio recommendations and projected returns are based on quantitative models and illustrative assumptions. They do not guarantee future performance and should not be considered professional financial advice.

## 👩‍💻 Author

**Shreya Mahajan**

Interested in Data Science, Financial Analytics, Machine Learning and building practical data-driven applications.

- GitHub: https://github.com/shreya975
- Project Repository: https://github.com/shreya975/Financial_Intelligence_Platform
- Live Application: https://financialintelligenceplatform-ixnjnesparf33mfmccwhy4.streamlit.app/

---

⭐ If you find this project interesting, consider giving the repository a star!
