# British Airways: End-to-End Customer Lifecycle Analytics
### Sentiment Scraping & Booking Prediction Pipeline

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)](https://scikit-learn.org/)
[![BeautifulSoup](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup4-green)](https://www.crummy.com/software/BeautifulSoup/)

## 📌 Project Overview
To maintain its competitive edge, British Airways needs to convert digital engagement into revenue. This project addresses two critical business needs through a dual-stream data science pipeline:

1.  **Brand Perception:** Analyzing thousands of unstructured third-party reviews to identify operational friction points.
2.  **Conversion Optimization:** Predicting the likelihood of a customer completing a booking to enable proactive marketing interventions.

---

## 🏗️ The Data Pipeline
The project follows a structured end-to-end lifecycle:
`Data Scraping` → `Text Preprocessing (NLP)` → `Sentiment Labeling` → `Feature Engineering` → `Random Forest Classification` → `Model Evaluation`

### 1. Sentiment Analysis Stream
* **Dataset:** 3,000+ reviews scraped from **SkyTrax**.
* **Tools:** `BeautifulSoup`, `NLTK`, `TextBlob`.
* **Insight:** Identified that while **60%** of reviews are positive, significant friction exists within "staff" and "verified" trip categories.

### 2. Predictive Modeling Stream
* **Dataset:** 50,000 rows of customer behavior metrics.
* **Target:** Successful booking completion.
* **Model:** Random Forest Classifier.
* **Accuracy:** **85.4%**

---

## 📊 Key Results & Insights
Through feature importance analysis, the following variables were identified as the strongest predictors of conversion:

* **Purchase Lead:** How far in advance the customer searches/books.
* **Flight Duration:** Longer hauls correlate differently with booking intent compared to short trips.
* **Operational Friction:** Sentiment analysis pinpointed specific service areas that negatively impact brand loyalty.

---

## 🛠️ Tech Stack
| Category | Tools/Libraries |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Manipulation** | Pandas, NumPy |
| **Web Scraping** | BeautifulSoup4, Requests |
| **Machine Learning** | Scikit-learn (Random Forest) |
| **NLP** | NLTK, TextBlob |
| **Visualization** | Matplotlib, Seaborn |

---

