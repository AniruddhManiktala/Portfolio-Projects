# **Twitter Cashtag Analysis: A Data-Driven Approach to Stock Mentions**

## **Project Overview**
This project explores the impact of Twitter discussions on stock mentions using a structured **PostgreSQL** database hosted on **AWS RDS**. By analyzing cashtags (e.g., `$AAPL`, `$TSLA`), we extract insights into market sentiment and stock popularity. The project leverages **data warehousing, materialized views, and indexing** to optimize query performance for financial analytics.

## **Objectives**
- ✅ Extract **stock-related tweets** from a dataset containing historical Twitter data.
- ✅ Map **cashtags to stock symbols** to analyze tweet frequency.
- ✅ Create **materialized views** to precompute and store tweet counts for efficient querying.
- ✅ Optimize query performance with **indexing**.
- ✅ Visualize **top-trending stocks** based on average tweet activity.

---

## **Technologies & Tools Used**
- **Database:** PostgreSQL (AWS RDS)
- **Scripting & Data Analysis:** Python (Pandas, Matplotlib, SQLAlchemy)
- **Query Optimization:** Materialized Views, Indexing
- **Visualization:** Matplotlib
- **Environment Management:** Conda, Jupyter Notebook

---

## **Key Highlights**
### **1️⃣ Data Pipeline & ETL Workflow**
- Extracted **Twitter cashtag data** and stock symbols from Yahoo Finance & NYSE datasets.
- Transformed raw tweet data to create a **normalized database schema**.
- Loaded structured data into **PostgreSQL on AWS RDS** for analysis.

### **2️⃣ Query Performance Optimization**
- Created a **materialized view** to precompute average tweet counts per stock symbol.
- Implemented **indexing** on cashtags and symbols to speed up queries.
- Improved **query execution time** from minutes to seconds.

### **3️⃣ Data Insights & Visualization**
- Ranked **top 10 most-discussed stocks** based on tweet volume.
- Found that **cryptocurrencies (`$ETH`, `$BTC`) and tech stocks (`$AAPL`, `$TSLA`) dominate discussions**.
- Used **Matplotlib** to create a **bar chart** showcasing tweet activity trends.

```python
import pandas as pd
import matplotlib.pyplot as plt

# Convert query output to DataFrame
df = query_output.DataFrame()

# Bar Chart: Average Tweet Activity by Stock Symbol
plt.figure(figsize=(10, 6))
plt.bar(df['nasdaqsymbol'], df['avg_tweet_count'], color='skyblue')
plt.title('Top 10 Stock Symbols by Average Tweet Activity', fontsize=14)
plt.xlabel('Stock Symbol', fontsize=12)
plt.ylabel('Average Tweet Count', fontsize=12)
plt.xticks(rotation=45, fontsize=10)
plt.tight_layout()
plt.show()
```

---

## **Results & Key Takeaways**
- 📌 **Crypto stocks dominate** Twitter discussions, with `$ETH` and `$BTC` leading.
- 📌 **Social media stocks** like `$TWTR` and `$SNAP` generate significant buzz.
- 📌 **Tech giants (`$AAPL`, `$TSLA`, `$MSFT`)** consistently rank high in mentions.
- 📌 **Materialized views significantly improved query speed**, making analysis scalable.

---

## **Next Steps & Enhancements**
🚀 Implement **real-time tweet tracking** using Twitter API.
🚀 Perform **sentiment analysis** on stock-related tweets.
🚀 Expand the dataset to **include NASDAQ and other global markets**.

---

## **Connect With Me**
💼 [LinkedIn](https://www.linkedin.com/in/amanikt/))  

---

