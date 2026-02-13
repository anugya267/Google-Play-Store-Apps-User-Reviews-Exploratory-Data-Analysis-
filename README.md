# 📊 Google Play Store Apps & User Reviews

A complete Exploratory Data Analysis (EDA) project on Google Play Store apps and user reviews to uncover insights about app categories, ratings, installs, pricing, and user sentiment.

## 🚀 Project Overview

The Google Play Store contains thousands of apps across multiple categories. This project performs data cleaning, preprocessing, visualization, and analysis to understand:

- 📱 Most popular app categories

- ⭐ Rating distribution patterns

- 📈 Install trends

- 💰 Free vs Paid app insights

- 🗣️ User review sentiment patterns

- 📊 Relationship between ratings, reviews, installs, and pricing

## 📂 Dataset Information

The dataset contains:

## 1️⃣ Apps Dataset

- App Name

- Category

- Rating

- Reviews

- Size

- Installs

- Type (Free/Paid)

- Price

- Content Rating

- Genres

- Last Updated

### 2️⃣ User Reviews Dataset

- App

- Translated Review

- Sentiment (Positive/Negative/Neutral)

- Sentiment Polarity

- Sentiment Subjectivity

## 🛠️ Technologies Used

- 🐍 Python

- 📦 Pandas

- 📊 NumPy

- 📉 Matplotlib

- 📈 Seaborn

- 📓 Jupyter Notebook

## 🔍 Data Cleaning Process

- Removed duplicate records

- Handled missing values

- Converted data types (Installs, Price, Size)

- Removed special characters (+, $, M, etc.)

- Filtered invalid ratings

## 📊 Key Insights
### 📌 1. Most Popular Categories

- Family

- Game

- Tools

- Business

### 📌 2. Rating Distribution

- Majority apps have ratings between 4.0 – 4.5

- Very few apps have rating below 3

### 📌 3. Free vs Paid Apps

- 90%+ apps are Free

- Paid apps generally have slightly higher ratings

### 📌 4. Installs vs Rating

- High installs don’t always mean high ratings

- Some niche apps have high ratings but low installs

### 📌 5. User Sentiment Analysis

- Majority reviews are Positive

- Negative reviews often relate to:

- Bugs

- Ads

- Performance issues

# 📈 Sample Visualizations
## 📊 Category Distribution

- Bar charts of top categories

## ⭐ Rating Distribution

- Histogram & KDE plots

## 📈 Installs Distribution

- Log-scaled plots

## 🗣️ Sentiment Analysis

- Pie charts

- Sentiment polarity distribution

## 📁 Project Structure
```
Google-Play-Store-EDA/
│
├── data/
│   ├── googleplaystore.csv
│   └── googleplaystore_user_reviews.csv
│
├── notebooks/
│   └── EDA_Google_Play_Store.ipynb
│
├── images/
│   └── visualizations.png
│
└── README.md
```
## ▶️ How to Run This Project

### 1. Clone the repositor
```
git clone https://github.com/your-username/google-play-store-eda.git
```
### 2. Navigate to the project folder
```
cd google-play-store-eda
```
### 3. Install required libraries
```
pip install pandas numpy matplotlib seaborn
```
### 4. Open Jupyter Notebook
```
jupyter notebook
```
### 5. Run EDA_Google_Play_Store.ipynb

## 📌 Future Improvements

- 🔥 Build a dashboard using Streamlit

- 🤖 Apply Machine Learning for rating prediction

- 📊 Deploy as a web app

- 🧠 Advanced NLP on user reviews


## 🙋‍♂️ Author
- Anugya Singh
  
Data Analyst | Data Enthusiast

📧 anugya.singh267@gmail.com

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and support the project!

