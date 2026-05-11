
📊 Predicting Price Moves with News Sentiment

Nova Financial Solutions – AI Mastery Week 1 Challenge

🧠 Project Overview

This project analyzes the relationship between financial news sentiment and stock market movements. The goal is to determine whether news headlines can be used as a predictive signal for stock price changes.

We combine:

📰 Financial news headlines (NLP analysis)
📈 Historical stock price data
📊 Technical indicators (SMA, RSI, MACD – in progress)
🔗 Statistical correlation analysis (future work)

The final objective is to build a pipeline that links news sentiment → market reaction → investment insights.

🏢 Business Objective

Nova Financial Solutions aims to enhance predictive financial analytics by understanding how news impacts stock prices.

This project supports:

Better forecasting accuracy
Sentiment-driven trading strategies
Data-informed investment decisions
📁 Project Structure
news-sentiment-analysis/
│
├── data/
│   ├── raw/
│   │   ├── raw_analyst_ratings.csv
│   │   ├── AAPL.csv
│   │   ├── META.csv
│   │   ├── GOOG.csv
│   │   ├── NVDA.csv
│   │   └── AMZN.csv
│
├── notebooks/
│   ├── task1_eda.ipynb
│   ├── task2_stock_analysis.ipynb
│
├── src/
│   └── (future modular scripts)
│
├── requirements.txt
├── .gitignore
└── README.md
📊 Dataset Description
📰 Financial News Dataset
Headline text
Publisher
Publication date
Stock ticker symbol
Article URL
📈 Stock Price Dataset
Open, High, Low, Close prices
Volume
Daily trading data
Multiple stocks: AAPL, META, GOOG, NVDA, AMZN
🔍 Completed Work (Interim Submission)
✅ Task 1: Exploratory Data Analysis (EDA)

Key analyses performed:

Headline length distribution
Publisher activity analysis
Publication trends over time
Hourly publishing patterns
Keyword frequency analysis
Topic modeling using LDA and TF-IDF

📊 Key Insight:
Financial news is highly concentrated among a few publishers and shows strong time-based clustering around market activity.

📈 Task 2 (Initial Progress): Stock Analysis
Loaded historical stock data for 5 companies
Cleaned and standardized datasets
Implemented Simple Moving Average (SMA)
Visualized price trends for initial understanding

📊 Key Insight:
SMA helps identify trend direction and smooth short-term volatility, forming the base for further technical indicators.

🧪 Planned Work (Task 3)
Sentiment analysis using:
VADER (primary)
TextBlob (baseline comparison)
Compute daily stock returns
Align sentiment with stock movements
Calculate Pearson correlation coefficient
Visualize sentiment vs returns relationship
🧠 NLP Approach
VADER Sentiment Analysis
Best suited for short financial headlines
Captures positive, neutral, and negative sentiment
Designed for social/news text
TextBlob
Used for baseline comparison
Simple polarity scoring
📊 Planned Visualizations
Sentiment vs Stock Returns (scatter plot)
Correlation heatmaps
News volume over time
Publisher activity charts
Technical indicator overlays (SMA, RSI, MACD)
📌 Key Insights (Interim)
Financial news is dominated by a small number of publishers
News volume spikes correlate with market events
Headlines contain strong financial signal words (earnings, price target, upgrade)
Stock trends show clear directional behavior when smoothed with SMA
⚠️ Challenges Faced
Handling inconsistent datetime formats across datasets
Processing large text datasets for NLP
Managing multiple stock datasets efficiently
GitHub file size limitations (resolved by cleaning repository)
Ensuring reproducible environment setup
🚀 Future Improvements
Full sentiment-to-price prediction model
Feature engineering with advanced technical indicators
Time-lag correlation analysis
Machine learning-based forecasting model
Portfolio-level strategy simulation
🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
NLTK / VADER
TA-Lib (planned)
Jupyter Notebook
Git & GitHub
👨‍💻 Author

Blen Debebe
AI Mastery Program – Week 1 Challenge
GitHub: https://github.com/debrouilard

📌 Status

## Task 1 Completed

- Descriptive statistics of headlines
- Publisher analysis
- Topic modeling using TF-IDF/LDA
- Time series analysis of news volume

✔ Task 2: In Progress
⏳ Task 3: Pending (Sentiment + Correlation Analysis)
