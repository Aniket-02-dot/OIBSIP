# 📱 Unveiling the Android App Market
## Google Play Store Analysis

### OASIS INFOBYTE – Data Analytics Internship

**Level:** 2  
**Task:** 4  

---

## 📌 Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) of the Google Play Store ecosystem. The analysis focuses on understanding app categories, ratings, installs, app size, pricing patterns, estimated revenue, and user sentiment.

The project uses real-world datasets containing Google Play Store application information and user reviews.

---

## 🎯 Objectives

- Clean and preprocess messy real-world data
- Analyze the distribution of apps across categories
- Identify the most saturated app categories
- Analyze app rating distribution
- Compare average ratings across categories
- Explore the relationship between app size and installs
- Analyze free vs paid applications
- Study the price distribution of paid apps
- Estimate potential revenue by app category
- Perform sentiment analysis on user reviews using VADER
- Compare positive and negative sentiment across app categories
- Create an interactive visualization using Plotly
- Generate data-driven insights for app developers

---

## 📂 Dataset

The project uses two datasets:

### 1. Google Play Store Apps Dataset

Contains information about applications such as:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres

### 2. Google Play Store User Reviews Dataset

Contains:

- App Name
- User Reviews
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK VADER
- Plotly
- Jupyter Notebook

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate applications
- Handled missing values
- Converted Reviews column to numeric format
- Cleaned Installs column by removing commas and "+" symbols
- Converted Price column to numeric format
- Converted app Size into MB
- Removed duplicate user reviews
- Removed reviews without review text

---

## 📊 Analysis Performed

### 1. Category Analysis

Analyzed the distribution of applications across Google Play Store categories to identify highly saturated markets.

### 2. Ratings Analysis

Explored:

- Distribution of app ratings
- Average rating by category
- Top-rated categories

### 3. App Size vs Installs Analysis

Performed correlation analysis and scatter plot visualization to understand whether application size influences the number of installs.

### 4. Pricing Analysis

Analyzed:

- Free vs Paid app distribution
- Price distribution of paid apps
- Estimated revenue by category

**Estimated Revenue Formula:**

Estimated Revenue = Installs × Price

> Note: This represents an estimate and not actual Google Play Store revenue.

### 5. Sentiment Analysis

Used **VADER Sentiment Analysis** to classify user reviews into:

- Positive
- Negative
- Neutral

### 6. Sentiment by Category

Merged user reviews with application categories to identify which categories receive the most positive and negative feedback.

### 7. Interactive Visualization

Created an interactive Plotly visualization to explore average app ratings across categories.

---

## 💡 Key Insights

### 1. Market Saturation

Highly saturated categories have greater competition. Developers should identify unique problems or underserved niches before launching an app.

### 2. App Size and Popularity

App size alone is not a strong predictor of installs. App quality, usefulness, user experience, and marketing likely have a greater influence.

### 3. Monetization Strategy

Free apps dominate the Google Play Store ecosystem. Developers may consider alternative monetization models such as subscriptions, advertisements, and in-app purchases.

### 4. Importance of User Feedback

User reviews provide valuable insights into customer satisfaction and potential areas for improvement.

---

## 📁 Project Structure

```text
DataAnalytics-L2-Task4-GooglePlayStoreAnalysis/
│
├── Google_Play_Store_Analysis.ipynb
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
├── README.md
└── screenshots/