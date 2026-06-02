<div align="center">

<br/>

```
██████╗ ██████╗  ██████╗ ███████╗██╗████████╗ █████╗ ██████╗  █████╗
██╔══██╗██╔══██╗██╔═══██╗██╔════╝██║╚══██╔══╝██╔══██╗██╔══██╗██╔══██╗
██████╔╝██████╔╝██║   ██║█████╗  ██║   ██║   ███████║██████╔╝███████║
██╔═══╝ ██╔══██╗██║   ██║██╔══╝  ██║   ██║   ██╔══██║██╔══██╗██╔══██║
██║     ██║  ██║╚██████╔╝██║     ██║   ██║   ██║  ██║██║  ██║██║  ██║
╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

### 🏬 Retail Business Intelligence & Predictive Analytics Platform

<br/>

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-ML%20Engine-FF6600?style=for-the-badge)](https://xgboost.readthedocs.io)
[![Prophet](https://img.shields.io/badge/Prophet-Forecasting-4ECDC4?style=for-the-badge)](https://facebook.github.io/prophet/)
[![Plotly](https://img.shields.io/badge/Plotly-Visualizations-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com)
[![Streamlit](https://img.shields.io/badge/Streamlit-Ready-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Version](https://img.shields.io/badge/version-2.0-C9A84C?style=for-the-badge)](https://github.com/NiceCoder69100971/profitara-retail-bi-pipeline)
[![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](LICENSE)

<br/>

**25 end-to-end analytics modules** — executive KPIs · ML profit prediction · time-series forecasting · customer intelligence

*Built by [Dhruv Jain](https://github.com/NiceCoder69100971)*

<br/>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NiceCoder69100971/profitara-retail-bi-pipeline/blob/main/Profitara_Analytics.ipynb)
&nbsp;
[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-181717?style=flat-square&logo=github)](https://github.com/NiceCoder69100971/profitara-retail-bi-pipeline)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Analytics Modules](#-analytics-modules)
- [Results & Metrics](#-results--metrics)
- [Tech Stack](#-tech-stack)
- [Dataset](#-dataset)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Author](#-author)

---

## 🧠 Overview

**Profitara** is a full-stack Retail BI and Customer Intelligence Platform that transforms raw transactional sales data into deep, actionable business intelligence. Built entirely in Python, it combines traditional BI analytics with cutting-edge machine learning — all wrapped in a custom dark-luxury Plotly theme.

The platform is designed to answer the questions retail businesses actually care about:

> *"Which products and regions are bleeding margin?"*
> *"Who are our Champions vs Lost customers?"*
> *"What will revenue look like in the next 90 days?"*
> *"Which transactions are anomalous and why?"*

Whether you're a business analyst, data scientist, or product owner — Profitara gives you the full picture in one notebook.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 📊 **25 Analytics Modules** | End-to-end coverage from KPIs to advanced ML |
| 🤖 **XGBoost Profit Predictor** | Gradient boosted model predicting per-order profit with R² scoring |
| 🔮 **Prophet Forecasting** | 90-day revenue forecast with upper/lower confidence intervals |
| 👥 **RFM Segmentation** | Customers classified as Champions · Loyal · At Risk · Lost |
| 💎 **CLV Scoring** | Customer Lifetime Value computed per customer with composite weighting |
| 🚨 **Anomaly Detection** | Isolation Forest flags the top 5% financially abnormal transactions |
| 🗺️ **US Sales Heatmap** | Choropleth map of revenue by state |
| 📉 **SHAP Explainability** | Feature importance for the profit prediction model |
| 🎨 **Dark Luxury Theme** | Custom Plotly theme — Gold `#C9A84C`, Teal `#4ECDC4`, Cream `#F5F0E8` on near-black `#0D0D0D` |
| 📦 **Plug-and-Play Dataset** | Works with Superstore CSV or any custom retail CSV that follows the same schema |

---

## 📊 Analytics Modules

### 🏁 Modules 1–5 · Core KPI Overview

| # | Module | What It Does |
|---|---|---|
| 1 | **Executive KPI Summary** | Total Revenue, Profit, Orders, Units Sold, Avg Margin, Unique Customers |
| 2 | **Sales by Category** | Grouped bar — Sales vs Profit across Furniture, Office Supplies, Technology |
| 3 | **Monthly Revenue Trend** | Line chart of monthly sales over the full date range |
| 4 | **Regional Performance** | Bar chart colored by margin% across all 4 US regions |
| 5 | **Segment Analysis** | Dual pie — Consumer vs Corporate vs Home Office by Sales & Profit |

### 📦 Modules 6–10 · Product & Sub-Category Intelligence

| # | Module | What It Does |
|---|---|---|
| 6 | **Top 10 Products** | Horizontal bar of top revenue-generating products |
| 7 | **Profitability Matrix** | Bubble scatter — Sales vs Profit vs Orders vs Margin% per sub-category |
| 8 | **Discount vs Profit** | Reveals exactly how aggressive discounting destroys margins |
| 9 | **Quantity Distribution** | Box plot of order quantity spread across categories |
| 10 | **Ship Mode Performance** | Revenue by shipping method overlaid with avg days-to-ship |

### 🧠 Modules 11–15 · Customer Intelligence

| # | Module | What It Does |
|---|---|---|
| 11 | **Top 10 Customers** | Horizontal bar ranked by revenue, colored by profit |
| 12 | **RFM Segmentation** | Recency-Frequency-Monetary scoring → Champion / Loyal / At Risk / Lost |
| 13 | **CLV Map** | Customer Lifetime Value scatter across order count and total spend |
| 14 | **Geographic Heatmap** | Choropleth of sales by US state |
| 15 | **Repeat vs One-Time** | Pie chart of customer loyalty split + repeat rate % |

### 🔮 Modules 16–20 · Predictive Analytics

| # | Module | What It Does |
|---|---|---|
| 16 | **Prophet Forecast** | 90-day daily sales forecast with upper/lower confidence intervals |
| 17 | **XGBoost Profit Predictor** | Gradient boosted regressor trained on 12 features to predict order profit |
| 18 | **SHAP Feature Importance** | Model explainability — which features drive profit most |
| 19 | **Actual vs Predicted** | Side-by-side line chart comparing ground truth vs model output |
| 20 | **Anomaly Detection** | Isolation Forest flags the top 5% financially abnormal transactions |

### 📅 Modules 21–25 · Advanced Seasonal Intelligence

| # | Module | What It Does |
|---|---|---|
| 21 | **YoY Growth** | Year-over-year revenue bar + growth % line on dual axes |
| 22 | **Quarterly Heatmap** | Year × Quarter revenue heatmap via Seaborn |
| 23 | **Return Risk Scoring** | Sub-categories ranked by discount + profit-loss risk score |
| 24 | **Revenue Waterfall** | Cumulative category revenue contribution waterfall chart |
| 25 | **Executive Report** | Automated text summary — best category, top region, peak month, model score |

---

## 📈 Results & Metrics

| Metric | Value |
|---|---|
| **XGBoost R² Score** | `0.75 – 0.88` (varies per run) |
| **Prophet Forecast Horizon** | 90 days forward from latest order date |
| **Anomalies Detected** | ~5% of transactions flagged by Isolation Forest |
| **RFM Segments** | 5 tiers: Champions · Loyal · Potential · At Risk · Lost |
| **CLV Scoring Weights** | Spend 60% · Profit 30% · Order Frequency 10% |
| **Dataset Size** | 9,994 orders · 21 columns · US Retail (2015–2018) |

---

## 🛠 Tech Stack

```
Language          Python 3.9+
Data Wrangling    Pandas · NumPy
Machine Learning  XGBoost · Scikit-learn · SHAP
Time Series       Prophet (Meta)
Visualization     Plotly · Matplotlib · Seaborn
Frontend          HTML · CSS  (Profitara_Dashboard.html)
Deployment        Streamlit-ready · Google Colab · Jupyter
```

### Installation

```bash
pip install pandas numpy matplotlib seaborn plotly \
            scikit-learn xgboost shap prophet openpyxl
```

---

## 📂 Dataset

Profitara runs on the **Superstore Sales Dataset** — a widely-used retail benchmark with ~10,000 US orders across 4 years (2015–2018).

| Field | Description |
|---|---|
| `Order Date` / `Ship Date` | Transaction and fulfillment timestamps |
| `Category` / `Sub-Category` | Product hierarchy (3 categories, 17 sub-categories) |
| `Region` / `State` | US geographic breakdown (4 regions, 49 states) |
| `Segment` | Customer type — Consumer · Corporate · Home Office |
| `Sales` / `Profit` / `Discount` | Core financial metrics |
| `Quantity` / `Ship Mode` | Operational metrics |
| `Customer ID` / `Customer Name` | Customer identity for RFM/CLV analysis |

> 💡 **Bring your own data:** Replace the CSV with any retail dataset that follows the same schema — all 25 modules run automatically.

---

## ⚡ Getting Started

### Option A — Google Colab *(Recommended)*

```
1. Click the "Open in Colab" badge at the top of this README
2. Runtime → Run All
3. Dataset loads automatically from URL
4. All 25 modules execute end-to-end
```

### Option B — Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/NiceCoder69100971/profitara-retail-bi-pipeline.git
cd profitara-retail-bi-pipeline

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost shap prophet openpyxl

# 3. Launch Jupyter
jupyter notebook Profitara_Analytics.ipynb

# 4. (Optional) View the standalone dashboard
open Profitara_Dashboard.html   # macOS
start Profitara_Dashboard.html  # Windows
```

### Option C — Dashboard Only *(No Python needed)*

Just open `Profitara_Dashboard.html` in any modern browser. Zero dependencies.

---

## 🗂 Project Structure

```
profitara-retail-bi-pipeline/
│
├── Profitara_Analytics.ipynb     ← Main notebook — all 25 modules
├── Profitara_Dashboard.html      ← Standalone interactive dashboard
├── Sample_-_Superstore.csv       ← Dataset (9,994 retail transactions)
└── README.md                     ← You are here
```

---

## 🖼 Screenshots

> The entire platform runs in a **dark-luxury theme** — Gold `#C9A84C` · Teal `#4ECDC4` · Cream `#F5F0E8` on near-black `#0D0D0D`.

| Module | Visual |
|---|---|
| 📊 KPI Dashboard | Executive summary with 6 core business metrics |
| 👥 RFM Pie Chart | Customer health distribution at a glance |
| 🔮 Prophet Forecast | Actuals + 90-day forecast with confidence band |
| 📉 SHAP Bar Chart | Feature importance driving profit prediction |
| 🗺️ US Heatmap | Choropleth of state-level revenue distribution |

---

## 👨‍💻 Author

<table>
  <tr>
    <td align="center">
      <b>Dhruv Jain</b><br/>
      B.Tech CSE (AI & Data Science) · BML Munjal University<br/><br/>
      <a href="https://github.com/NiceCoder69100971">
        <img src="https://img.shields.io/badge/GitHub-NiceCoder69100971-181717?style=flat-square&logo=github" />
      </a>
      &nbsp;
      <a href="https://www.linkedin.com/in/dhruvjain1824">
        <img src="https://img.shields.io/badge/LinkedIn-dhruvjain1824-0A66C2?style=flat-square&logo=linkedin" />
      </a>
    </td>
  </tr>
</table>

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

<div align="center">

**⭐ If Profitara helped you, drop a star — it genuinely means a lot.**

*Built with Python, curiosity, and too much coffee.*

</div>
