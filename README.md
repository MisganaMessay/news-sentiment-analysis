# 📈 Financial News Sentiment & Stock Analysis

## 📁 Project Structure
- `data/raw/`: Contains the original FNSPID dataset (Git-ignored).
- `src/`: Reusable Python modules for sentiment scoring and data cleaning.
- `notebooks/`: 
    - `eda_news.ipynb`: Advanced text analysis (TF-IDF, Time-series spikes).
    - `quantitative_analysis.ipynb`: Technical indicators (SMA, RSI, MACD).
- `tests/`: Unit tests for ensuring data processing integrity.
- `scripts/`: Utility scripts for automated data fetching.

## 🛠️ Advanced Setup
1. **Environment:** `python -m venv venv` and `.\venv\Scripts\activate`.
2. **Dependencies:** `pip install -r requirements.txt`.
3. **Data Placement:** Ensure `raw_analyst_ratings.csv` is in `data/raw/`.

## 📊 Analytical Methodology
### Task 1: NLP & EDA
- **Text lengths:** Distribution analyzed via Histograms and Boxplots to identify snippet-style news.
- **Theme Extraction:** Implemented **TF-IDF Vectorization** to move beyond simple word counts and identify industry-specific terminology.
- **Spike Analysis:** Automated detection of volume spikes, cross-referenced with historical market events (e.g., 2020 volatility).