SENTIMENT ANALYSIS ON TWITTER DATA:

This project performs sentiment analysis on tweets using natural language processing techniques. It focuses on identifying the sentiment (Positive, Negative, or Neutral) of tweets related to specific brands/entities and visualizing the patterns using bar plots and word clouds.

DATASET:

•File Used: twitter_training.csv
•Format: CSV
•Columns:
°ID: Tweet ID
°Entity: Brand or company name (e.g., Facebook, Google)
°Sentiment: (Original sentiment label, not used in classification)
°Tweet: The actual tweet content

LIBRARIES USED:

•PANDAS
•numpy
•nltk
•textblob
•matplotlib
•seaborn
•wordcloud

PROJECT WORKFLOW:

1. Data Loading and Cleaning

Dataset is loaded and given custom column names.
Rows with missing tweets are dropped.

2. Sentiment Scoring

Sentiment polarity is computed using TextBlob.
Tweets are labeled as:
Positive (polarity > 0)
Negative (polarity < 0)
Neutral (polarity == 0)

3. Brand-wise Analysis

A specific brand (e.g., Facebook) is filtered from the dataset.
Sentiment distribution is analyzed for that brand.

4. Visualizations

Bar Plot of sentiment counts using Seaborn.
WordClouds for each sentiment category to highlight frequent terms.
Sample Output
Sentiment distribution plot for a brand (e.g., Facebook)
WordClouds for Positive, Negative, and Neutral tweets

HOW TO RUN:

1.Open the notebook in Google Colab.
2.Upload the twitter_training.csv file when prompted.
3.Change the brand_name variable to analyze a different brand.
4.Run all cells to view visualizations and sentiment classification.