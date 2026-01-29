# Google Play Store Data Analysis

 Project Overview
This project analyzes the Google Play Store app market to understand app distribution, popularity, ratings, pricing trends, and user sentiment. Using Python and data visualization techniques, the project extracts meaningful insights from app metadata and user reviews.

The analysis combines exploratory data analysis (EDA) with sentiment analysis, making it a complete internship-level data analytics project.

---

 Objectives
- Clean and preprocess Google Play Store datasets  
- Analyze app distribution across categories  
- Study key metrics such as ratings, installs, size, and pricing  
- Perform sentiment analysis on user reviews  
- Visualize trends and insights effectively  

---

 Dataset Information
The project uses two datasets from Kaggle:

 apps.csv
Contains app-level information:
- App Name  
- Category  
- Rating  
- Reviews  
- Size  
- Installs  
- Price  
- Type (Free / Paid)  

 user_reviews.csv
Contains user feedback data:
- App Name  
- Translated Review  
- Sentiment (Positive / Neutral / Negative)  
- Sentiment Polarity  
- Sentiment Subjectivity  

---

 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Project Workflow

 Data Cleaning & Preparation
- Loaded datasets separately  
- Removed duplicate entries  
- Handled missing values  
- Converted columns like **Installs, Price, and Size** into numeric format  

 Category Exploration
- Analyzed number of apps per category  
- Visualized category distribution using bar charts  
- Identified competitive and niche categories  

 Metrics Analysis
- Analyzed rating distribution  
- Studied app popularity using install counts  
- Compared free vs paid apps  
- Explored relationship between app size and ratings  

 Sentiment Analysis
- Cleaned user reviews dataset  
- Analyzed sentiment distribution  
- Visualized positive, neutral, and negative reviews  

 Data Visualization
- Histograms for ratings and installs  
- Bar charts for categories and sentiment analysis  
- Scatter plots for size vs rating  

Conclusion
This project provides valuable insights into the Google Play Store ecosystem by analyzing app metrics and user sentiment. It helps understand market competition, user preferences, and app performance trends, making it useful for developers and analysts.
