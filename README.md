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
## 🧪 Testing & Quality Assurance
To ensure the reliability of technical indicators, we implement:
- **Manual Math Validation:** Periodically verifying library outputs against raw rolling-window calculations (found in Task 2 notebooks).
- **Automated CI:** GitHub Actions verify environment stability and library compatibility on every push.

## 🤝 Contribution & Scaling
To scale this project for more stock symbols:
1. **Branching:** All new features must be developed on a named branch (e.g., `task-2-revision`).
2. **Modularization:** Reusable cleaning logic is stored in the `src/` directory.
3. **Integration:** New indicators must be validated against TA-Lib standards before being merged into the main pipeline.