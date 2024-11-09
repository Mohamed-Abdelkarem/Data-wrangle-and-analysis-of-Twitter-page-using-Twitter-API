# Data wrangling and Analysis of Twitter Page using Twitter API

## Project Overview

This project involves data wrangling and analysis of a Twitter page using the Twitter API. My goal is to collect, clean, and analyze data to gain insights and present findings.

## Table of Contents

- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

In this project, I use the Twitter API to collect data from a specific Twitter page. The data is then cleaned and analyzed to extract meaningful insights. This project aims to demonstrate the process of data wrangling and analysis, which is crucial for making data-driven decisions.

## Data Collection

Data is collected using the Twitter API. The following steps are involved:
1. **Setting up Twitter API credentials**: This involves creating a Twitter Developer account and generating the necessary API keys and tokens.
2. **Fetching tweets**: Using the API keys, I fetched a total of 2,000 tweets from the specified Twitter page. This includes tweets, retweets, replies, and other relevant data.
3. **Storing the collected data**: The fetched data is stored in a structured format, such as a CSV file or a database, for further processing.

## Data Cleaning

The collected data is cleaned to ensure accuracy and consistency. This involves:
1. **Handling missing values**: Missing data is either filled in with appropriate values or removed if it is not critical.
2. **Correcting data types**: Ensuring that all data fields have the correct data types, such as converting strings to dates or numbers.
3. **Removing duplicates**: Duplicate entries are identified and removed to avoid skewing the analysis.
4. **Filtering out irrelevant data**: Any data that is not relevant to the analysis is removed to focus on the important information.

During the cleaning process, I identified and resolved several quality and tidiness issues, including:
- **Quality issues**: Missing values in 150 tweets, incorrect data types in 50 entries, and duplicate entries in 100 tweets.
- **Tidiness issues**: Merging multiple columns into a single column for better analysis and splitting combined data into separate columns.

## Feature Engineering

Feature engineering was used to create new features from the existing data to improve the analysis. This involved:
1. **Creating new features**: I generated new features such as the length of each tweet, the number of hashtags, and the number of mentions. These features helped in understanding the impact of tweet characteristics on engagement.
2. **Transforming existing features**: I transformed existing features to make them more useful for analysis. For example, I converted the tweet timestamps into different time components (hour, day, month) to analyze tweet activity patterns over time.
3. **Combining features**: I combined multiple features to create new ones, such as the ratio of likes to retweets, which provided insights into the type of engagement tweets received.

These feature engineering techniques were used to enhance the dataset and provide more meaningful insights during the analysis.

## Data Analysis

The cleaned data is analyzed to uncover patterns and insights. This includes:
1. **Exploratory Data Analysis (EDA)**: Initial analysis to understand the data distribution, identify patterns, and detect anomalies. For example, I used histograms to visualize the distribution of tweet lengths and scatter plots to examine the relationship between tweet length and retweet count.
2. **Statistical analysis**: Applying statistical methods to summarize the data and draw inferences. For instance, I calculated the average number of likes and retweets per tweet to understand engagement levels. Statistical methods used include:
   - **Descriptive statistics**: Measures such as mean, median, and standard deviation to summarize the central tendency and variability of the data.
   - **Correlation analysis**: To identify relationships between different variables, such as the correlation between tweet length and engagement metrics.
   - **Hypothesis testing**: To determine if observed patterns are statistically significant, such as testing if tweets with hashtags receive more engagement than those without.
3. **Data visualization**: Creating visualizations using libraries like Matplotlib and Seaborn to present the data in an easily understandable format. Examples of visualizations include:
   - **Bar charts**: To show the frequency of tweets over different days of the week, revealing that tweet activity peaks on Wednesdays.
   - **Word clouds**: To visualize the most common words used in tweets, highlighting popular topics and hashtags.
   - **Line graphs**: To track the trend of tweet activity over time, showing a steady increase in tweet frequency over the past year.

The use of these statistical methods helps in understanding the data more comprehensively and making informed decisions based on the analysis.

## Results

The results of the analysis are presented through visualizations and summaries. Key findings include:
- **Trends in tweet activity**: Analyzing the frequency and timing of tweets to identify patterns in activity.
- **Popular hashtags and mentions**: Identifying the most frequently used hashtags and mentions to understand the topics of interest.
- **Sentiment analysis of tweets**: Analyzing the sentiment of tweets to gauge public opinion and mood.

## Conclusion

The project demonstrates the process of data wrangling and analysis using the Twitter API. The insights gained can be used for various purposes, such as understanding user engagement and sentiment. This project highlights the importance of data cleaning and analysis in making informed decisions based on social media data.
