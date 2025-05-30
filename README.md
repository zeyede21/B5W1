# 📰 News Sentiment Analysis for Stock Price Prediction

## 📌 Project Overview

This project aims to explore and analyze financial news headlines to identify patterns, key topics, and publication behavior that may influence stock prices. The goal is to understand how the frequency and content of news articles can be correlated with stock price movement — a crucial step for building predictive models.

In **Task 1**, we:

- Cleaned and preprocessed raw news data
- Analyzed publication frequency and top publishers
- Extracted keyword topics using NLP techniques (TF-IDF + NMF)
- Visualized trends using time series and bar charts
- Saved cleaned data for future technical and sentiment-based modeling

## 🗂️ Project Structure

├── .github/
│ └── workflows/unittests.yml # (future use)
├── .vscode/settings.json # (optional IDE config)
├── src/ # Source code folder
├── notebooks/
│ └── eda_news_analysis.ipynb # Exploratory analysis notebook
├── scripts/ # Helper scripts (if needed)
├── tests/ # Unit tests (TBD)
├── requirements.txt # List of Python dependencies
├── README.md # This file

## ▶️ How to Run the Code

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/news-sentiment-analysis.git
   cd news-sentiment-analysis
   ```
2. **(Optional) Create a Virtual Environment**
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
3. **Install Dependencies**
   pip install -r requirements.txt
4. **Run the Notebook**
   **Open the notebook in Jupyter or VSCode:**
   notebooks/eda_news_analysis.ipynb
5. **Generated Outputs**
   top_publishers.png: Visual of most active news sources

   articles_over_time.png: Timeline of article frequency

   cleaned_news_data.csv: Cleaned dataset for modeling
