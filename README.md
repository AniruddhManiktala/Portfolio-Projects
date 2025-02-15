📊 Oil & Gas Industry Analysis

This project presents a data-driven analysis of the Oil & Gas industry using Python, focusing on financial performance and text-based insights from 10-K reports (1994–2020). The analysis involved filtering industry-specific data using SIC codes, calculating key metrics like stock prices, sales, and ROA, and visualizing trends through line charts. Text preprocessing steps such as case normalization, punctuation removal, and stopword elimination were applied to extract meaningful keywords using TF-IDF and frequency-based methods, with results showcased via word clouds. A Word2Vec model was trained on the cleaned text to identify industry-relevant terms and analyze competitive positioning through cosine similarity. Additionally, firm-level performance across key financial indicators was examined to assess market trends, with a dedicated analysis of the 2008 financial crisis's impact. The findings offer actionable insights into industry dynamics, competitive positioning, and long-term performance trends.

🚀 Technologies Used

Python (Pandas, NumPy, Matplotlib, NLTK, Scikit-Learn, Gensim)

WordCloud

Jupyter Notebooks

📂 Project Structure

Data Filtering & Analysis: Industry-specific data extraction and financial analysis.

Text Cleaning: Preprocessing of 10-K reports for keyword extraction.

Keyword Analysis: TF-IDF and frequency-based keyword extraction with visual word clouds.

Word Embedding & Competitor Identification: Word2Vec model training for competitor analysis.

Performance Insights: Financial trend analysis across firms and historical events like the 2008 crisis.

📈 Key Insights

Identification of key players and trends in the Oil & Gas industry.

Insights into firms most impacted by the 2008 financial crisis.

Competitive landscape analysis using Word2Vec embeddings.

🛠️ How to Run

Clone the repository.

Install dependencies using pip install -r requirements.txt.

Run the Jupyter Notebook to reproduce the analysis.

🎯 Future Directions

Extend analysis to other industry sectors.

Incorporate advanced NLP techniques for sentiment analysis.
