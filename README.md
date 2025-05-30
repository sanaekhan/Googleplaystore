 Google Play Store Analysis
This project explores and analyzes data from the Google Play Store to gain insights into app trends, user behavior, and factors influencing ratings and downloads. It combines datasets of app metadata and user reviews for a complete analysis.

📌 Project Objectives
Clean and preprocess the Google Play Store datasets

Analyze app categories, size, price, ratings, and installs

Investigate user sentiments and app feedback

Correlate features like app type, genre, and price with success metrics

Visualize the distribution and trends of mobile applications

🛠 Tools & Technologies Used
Python – Primary programming language

Pandas & NumPy – Data manipulation and analysis

Matplotlib & Seaborn – Data visualization

Jupyter Notebook – Interactive data analysis environment

📁 Dataset Information
googleplaystore.csv

Contains metadata for apps: name, category, rating, size, installs, price, content rating, genres, etc.

googleplaystore_user_reviews.csv

Contains user reviews including review text and sentiment (positive, negative, neutral).

Source: Public dataset available on Kaggle

🧹 Data Cleaning Highlights
Removed duplicate app entries

Handled incorrect data types and missing values

Converted size, price, and install columns into numeric formats

Merged app data with user reviews for sentiment-based analysis

📊 Key Exploratory Data Analysis
Most popular categories by number of apps

Distribution of app ratings, reviews, and installs

Average rating by app type (Free vs. Paid)

Top-rated apps and apps with the highest number of installs

Sentiment analysis on user reviews

📌 Key Insights
Games, Tools, and Productivity are among the most frequent app categories

Most apps are free, but paid apps tend to have slightly higher average ratings

Larger apps generally belong to categories like Games or Tools

Positive sentiment dominates user reviews, but low-rated apps show more negative feedback

Many apps have inflated download numbers but moderate ratings, suggesting download count isn't always linked to quality

