# Brainwave_Matrix_Intern_dataSci_DataAna_Task-2
Instagram Sentiment Analysis

Overview

This project aims to assess the sentiment of Instagram post captions and visualize trends over time. By leveraging VADER sentiment analysis, captions are categorized into Positive, Neutral, or Negative sentiments. The analysis includes visualizations for sentiment distribution, trends, and engagement metrics such as likes and comments.

Workflow

1. Importing Libraries and Loading Data

Libraries Utilized: pandas, matplotlib, nltk, seaborn

Data Source: CSV file loaded via pd.read_csv()

2. Data Preprocessing

Text Cleaning: Remove special characters and convert text to lowercase.

Handling Missing Data:

Default values for missing location and username fields.

Mean values for numerical fields like followers and following.

3. Sentiment Analysis

VADER Sentiment Analysis: Assigns sentiment scores to captions.

Classification: Posts are categorized as Positive, Neutral, or Negative based on the sentiment score.

4. Time-Based Analysis

Trend Analysis: Average sentiment scores over time visualized through a line plot.

5. Visualizations

Pie Chart: Sentiment distribution (Positive, Neutral, Negative).

Histogram: Distribution of sentiment scores.

Boxplot: Sentiment score distribution by sentiment category.

Word Cloud: Common words in each sentiment category.

Bar Chart: Count of posts by sentiment.

Heatmap: Correlation between likes, comments, followers, and sentiment scores.

Boxplot: Likes and comments distribution by sentiment.

Key Insights

Trends Analysis: Tracks sentiment fluctuations over time.

Engagement Metrics: Analyzes the relationship between likes, comments, and sentiment.

Word Clouds: Identifies frequent words in Positive, Neutral, and Negative captions.

Visual Examples

Sentiment Distribution: Pie chart showing the percentage of each sentiment category.

Sentiment Trends: Line plot displaying sentiment progression over time.

Word Cloud: Visual representation of common words by sentiment.

Correlation Heatmap: Displays correlations between likes, comments, followers, and sentiment scores.
