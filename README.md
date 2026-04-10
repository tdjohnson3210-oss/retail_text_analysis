# Text Mining & Sentiment Analysis of Retail Customer Reviews
This project analyzes 2,000+ ASOS customer reviews using text mining, VADER sentiment scoring, and a TF‑IDF + Logistic Regression model. The goal is to understand customer sentiment, identify common themes, and compare rule‑based vs. machine‑learning sentiment classification.

Methods
- Text cleaning and preprocessing
- Tokenization + stopword removal
- VADER sentiment scoring on raw text
- Word clouds and frequency analysis
- TF‑IDF feature extraction
- Logistic Regression classifier (balanced classes)
  
Key Findings
- VADER labeled most reviews as positive, but often missed mixed or context‑dependent sentiment.
- The ML model achieved 81% accuracy and performed better across negative and neutral classes.
- Common themes across reviews included customer service, delivery issues, and product expectations.
- Words like “customer” and “service” appeared in both positive and negative reviews, showing sentiment depends on context.
  
Tools
Python, Pandas, NLTK, VADER, Scikit‑learn, Matplotlib, WordCloud
