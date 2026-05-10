# 📈 Financial News Sentiment and Stock Price Analysis

## 🎯 Business Objective
This project was developed for :contentReference[oaicite:0]{index=0} with the goal of enhancing predictive analytics by analyzing the relationship between financial news sentiment and stock price movements.

The project builds an analytical pipeline that:
- Quantifies financial news sentiment using NLP techniques
- Computes technical indicators from historical stock market data
- Identifies correlations between sentiment trends and market behavior

The final objective is to generate actionable investment insights and improve forecasting accuracy for financial decision-making.

---

## 📊 Project Progress (Interim)

### ✅ Task 1: Exploratory Data Analysis (EDA)
Performed exploratory analysis on the **FNSPID dataset** (~1.4 million rows), including:
- Publisher activity analysis
- Publication frequency trends
- Time-series distribution of news articles
- Dataset quality checks and profiling

### ✅ Task 2: Quantitative Analysis
Implemented technical analysis indicators for target stocks (e.g., AAPL) using:
- Simple Moving Average (SMA)
- Relative Strength Index (RSI)
- Moving Average Convergence Divergence (MACD)

Data was collected using:
- `yfinance`
- `pandas_ta`

---

## 🪜 The Three-Layer Framework

Our analysis follows the **“Ladder of Insight”** framework:

1. **What is changing?**  
   Identify market trends, volatility patterns, and news volume spikes.

2. **What did it cause?**  
   Measure correlations between sentiment fluctuations and stock price returns.

3. **What does it demand?**  
   Generate data-driven investment insights and strategic recommendations.

---

## 📁 Project Structure

```text
news-sentiment-analysis/
│
├── notebooks/
│   ├── eda_analysis.ipynb
│   └── technical_indicators.ipynb
│
├── data/
│   └── raw/
│       └── (large CSV files ignored via .gitignore)
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Setup & Reproducibility

### 1️⃣ Clone the Repository

```cmd
git clone https://github.com/MisganaMessay/news-sentiment-analysis.git
cd news-sentiment-analysis
```

### 2️⃣ Create and Activate Virtual Environment

```cmd
python -m venv venv
.\venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```cmd
pip install -r requirements.txt
```

---

## 💻 Tech Stack

### 🐍 Programming Language
- Python 3.12.4

### 📊 Data Analysis
- Pandas
- NumPy
- SciPy
- Pandas-TA

### 🧠 Natural Language Processing (NLP)
- NLTK (VADER Sentiment Analysis)

### 📈 Visualization
- Matplotlib
- Seaborn

### ⚙️ DevOps & Version Control
- Git
- GitHub Actions (CI/CD)

---

## 🚀 Future Work

Planned next steps include:
- Advanced sentiment modeling using transformer-based NLP models
- Event-driven market impact analysis
- Predictive machine learning models for stock forecasting
- Real-time news ingestion and sentiment dashboards

---

## 📌 Key Focus Areas

- Financial News Sentiment Analysis
- Technical Indicator Engineering
- Time-Series Analysis
- Correlation & Predictive Analytics
- Investment Insight Generation

---