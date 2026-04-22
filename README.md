British Airways: Data Science Technical Pipeline

End-to-End Customer Lifecycle Analytics: Sentiment Scraping to Booking Prediction

1. Business Problem Statement
To maintain its competitive edge, British Airways needs to convert digital engagement into revenue. This project addresses two critical needs:
    Brand Perception: Analyzing thousands of unstructured third-party reviews to identify operational friction points.
    Conversion Optimization: Predicting the likelihood of a customer completing a booking to enable proactive marketing interventions.

2. Dataset & Pipeline
Sentiment Data: 3,000+ reviews scraped from SkyTrax using BeautifulSoup.113
Booking Data: 50,000 rows of customer behavior metrics (flight duration, lead time, route, etc.).15
The Pipeline: Data Scraping -> Text Preprocessing (NLP) -> Sentiment Labeling -> Feature Engineering -> Random Forest Classification -> Model Evaluation.

3. Key Insights & Results
Customer Sentiment: 60% of reviews are positive, but key friction points were identified in "staff" and "verified" trip categories.
Predictive Power: Built a Random Forest model with 85.4% accuracy.
Top Predictors: purchase_lead (how far in advance they book) and flight_duration are the strongest indicators of whether a customer will complete a booking.

4. Tech Stack
Language: Python 3.x
Libraries: Scikit-learn, Pandas, NLTK, TextBlob, BeautifulSoup, Matplotlib.14
