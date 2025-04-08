# ✈️ Sentiment Analysis of British Airways Customer Reviews

A data science project that scrapes and analyzes customer reviews of British Airways to uncover sentiment trends, frequent themes, and seasonal patterns in customer feedback.

---

## 📌 Overview

This project involves:
- **Web scraping** 5,000+ verified and unverified reviews from [airlinequality.com](https://www.airlinequality.com).
- **Text cleaning and preprocessing** for sentiment analysis.
- **Machine learning classification** of sentiments (positive/negative).
- **Visualizations** to explore sentiment trends over time and highlight common keywords in feedback.

---

## 🔧 Tools & Technologies

- **Python**
- `BeautifulSoup`, `Requests` – for web scraping  
- `Pandas`, `NumPy` – data manipulation  
- `Scikit-learn` – ML model building (e.g., Logistic Regression)  
- `Matplotlib`, `Seaborn` – data visualization  
- `NLTK`, `re` – text preprocessing  

---

## 💡 Key Features

- Scrapes reviews along with:
  - Review text
  - Verification status (Verified / Not Verified)
  - Published date
- Cleans and processes textual data to remove noise
- Converts dates to standard datetime format
- Classifies reviews into **positive** or **negative** sentiment using a supervised ML model
- Visualizes:
  - Most frequent words in positive/negative reviews
  - Sentiment trends using a **heatmap over months and years**
  - Distribution of review sentiments
  - Temporal patterns in customer satisfaction

---
