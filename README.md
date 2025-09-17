# Business Impact of Sentiment Analysis of Amazon Reviews

*A Case Study of Omron Blood Pressure Monitors*

## 📌 Project Overview

This project explores the **business impact of sentiment analysis** on Amazon reviews for Omron Blood Pressure Monitors. Using **VADER** (a lexicon and rule-based sentiment analysis tool) and **RoBERTa** (a transformer-based deep learning model), we analyze customer feedback to identify product strengths, weaknesses, and opportunities for business improvement.

The goal is to bridge the gap between **customer feedback** and **data-driven business decisions**, enabling Omron to improve product design, customer satisfaction, and marketing strategies.

---

## 📊 Key Features

* **Web Scraping**: Extracted 851+ reviews of Omron BP monitors from Amazon.in using `requests` and `BeautifulSoup`.
* **Preprocessing Pipeline**:

  * Tokenization
  * Stop-word removal
  * Lemmatization
* **Sentiment Analysis Models**:

  * **VADER** for quick, rule-based sentiment classification.
  * **RoBERTa** for contextual, transformer-based classification.
* **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score.
* **Visualization**: Bar charts, pie charts, and word clouds for better interpretability.
* **Actionable Insights**: Recommendations for product improvement and marketing strategies.

---

## 📈 Results

| Metric    | VADER | RoBERTa |
| --------- | ----- | ------- |
| Accuracy  | 77.9% | 69.5%   |
| Precision | 81.5% | 86.9%   |
| Recall    | 77.9% | 69.5%   |
| F1-Score  | 79.5% | 75.8%   |

* **VADER** performed better overall in terms of balanced accuracy and recall.
* **RoBERTa** achieved higher precision but struggled with neutral/negative reviews.

---

## 💡 Business Insights

* **Product Improvement Needs**: Accuracy, app performance, battery life, and cuff design.
* **Marketing Strategies**:

  * Emphasize product reliability and brand trust.
  * Highlight ease of use and app integration.
  * Promote accuracy with medical endorsements.
  * Run targeted campaigns for key features.
  * Provide multilingual customer support and education.

---

## 🛠️ Tech Stack

* **Languages**: Python
* **Libraries**: `NLTK`, `pandas`, `numpy`, `requests`, `BeautifulSoup`, `transformers`, `seaborn`, `matplotlib`
* **Models**: VADER, RoBERTa (`cardiffnlp/twitter-roberta-base-sentiment`)


## 📖 Reference

This project was developed as part of the **BDM Capstone Project** for the IITM Online BS Degree Program.
