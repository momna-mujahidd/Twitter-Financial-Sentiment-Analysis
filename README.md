# Twitter Financial Sentiment Analysis Dashboard
This project is a ** Twitter financial sentiment analysis** built to analyze finance-related tweets for sentiment insights. It simulates real-time data processing and visualization using PostgreSQL, Python, and Power BI.

## 🚀 Project Summary
- Goal: Provide sentiment trends (Bullish, Bearish, Neutral) from financial tweets, along with confidence scores and keyword analysis, visualized through a professional Power BI dashboard.
- Data: ~12,000 annotated finance-related tweets (static dataset simulating real-time ingestion).
- Key Features:
  - Data ingestion, transformation, and enrichment (date simulation, sentiment confidence, keyword extraction).
  - ETL process using Python + PostgreSQL for storing, querying, and managing data.
  - Power BI dashboard displaying key KPIs, trends, and sentiment distribution.

## 🛠️ Tools & Technologies
- Python: Data processing, transformation, and database loading.
- PostgreSQL (Railway): Cloud-hosted database for storing tweet data.
- Power BI: Interactive dashboard with measures, KPIs, and custom visuals.
- ODBC Connection: For integrating Power BI with PostgreSQL.

## ⚡ Key Components

- **ETL Pipeline**
  - Simulates tweet date to mimic live streaming.
  - Adds confidence scores (e.g., softmax-like simulated values).
  - Extracts top keywords from bullish/bearish tweets.
  - Loads processed data into PostgreSQL.

- **Power BI Dashboard**
  - KPIs: Total tweets, tweets today, average confidence.
  - Visuals: Sentiment trends over time, average confidence by sentiment, keyword frequency charts.
  - Filters: Sentiment type, date filters for exploring data.

## 📊 Dashboard Highlights
- Total Tweets
- Tweets Today / Yesterday
- Average Sentiment Confidence
- Sentiment Distribution
- Keyword Analysis (Bullish/Bearish terms)
- Sentiment Trends Over Time

## 📌 How It Works
1️⃣ Python script processes raw CSV files, enriches them, and inserts into PostgreSQL.  
2️⃣ Power BI connects via ODBC to PostgreSQL for real-time querying.  
3️⃣ Interactive visuals and KPIs update with new inserted data.

## ⚠️ Notes
- The dataset is static and used to **simulate real-time** behavior. No actual live tweets are streamed.
- ODBC connection requires correct setup and may need SSL adjustments depending on your host.

# 🖼 Dashboard Preview
dashboard_preview.png

## 📁 Files Included
- `Twitter financial sentiment analysis.pbix` – Main Power BI dashboard
- `sent_valid.csv` and `sent_train.csv` – Dataset used for report
- `dashboard preview.png` – Dashboard screenshots
- `Twitter_Financial_Sentiment_Analysis.ipynb` – Code(Database included)

