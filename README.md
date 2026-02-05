# Task-04: Social Media Sentiment Analysis 

## Project Overview
This project focuses on analyzing and visualizing sentiment patterns in social media data to understand public opinion and attitudes toward different topics or brands. The analysis uses Twitter data and applies Natural Language Processing (NLP) techniques to classify sentiments into Positive, Negative, and Neutral categories.

This task is part of the **Prodigy Infotech Data Science Internship**.

## Dataset Information
- **Dataset Name:** twitter_training.csv  
- **Source:** Prodigy Infotech (Task-04 Dataset)
- **Data Type:** Social Media Text (Tweets)

### Dataset Columns:
| Column Name | Description |
|------------|-------------|
| id | Unique tweet identifier |
| topic | Brand or topic related to the tweet |
| sentiment | Original sentiment label (Positive, Negative, Neutral, Irrelevant) |
| text | Tweet content |

## Data Cleaning & Preprocessing
The dataset was cleaned and prepared using the following steps:
- Removed missing values from text data
- Removed duplicate records
- Converted text to lowercase
- Removed URLs, special characters, and numbers
- Removed stopwords using NLTK
- Created a cleaned text column for analysis

## Sentiment Analysis
- Sentiment analysis was performed using **VADER Sentiment Analyzer**
- VADER is suitable for social media text due to its handling of informal language
- Sentiment scores were generated and classified as:
  - **Positive**
  - **Negative**
  - **Neutral**
- Tweets labeled as *Irrelevant* were excluded from sentiment polarity comparison

## Data Visualization
The following visualizations were created:
- Sentiment distribution bar chart
- Sentiment score distribution histogram
- Sentiment comparison across different topics/brands

These visualizations help in identifying public opinion trends and sentiment patterns.

## Key Insights
- Negative sentiment dominates the dataset, indicating higher dissatisfaction among users
- Positive sentiment shows significant engagement
- Neutral sentiment represents balanced or informational opinions
- Irrelevant tweets are minimal, showing most data is topic-related

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK (VADER, Stopwords)

## Conclusion
In this task, social media data was analyzed to understand public opinion and sentiment toward different topics and brands. The dataset was first cleaned by removing missing values, duplicate records, and irrelevant noise from the text, ensuring the data was suitable for analysis. Text preprocessing techniques such as lowercasing, 
stopword removal, and elimination of URLs and special characters were applied to improve the quality of the textual data.Sentiment analysis was performed using the VADER sentiment analyzer, which is well-suited for short and informal social media content. Tweets were classified into positive, negative, and neutral categories based on their
sentiment scores. Irrelevant tweets were excluded from polarity comparison, as they do not represent sentiment orientation.The visualizations revealed that negative sentiment dominates the dataset, indicating a higher level of dissatisfaction or criticism among users. Positive sentiment also shows a significant presence, reflecting favorable 
opinions, while neutral sentiment represents users with informational or balanced views. Irrelevant tweets were minimal, suggesting that most tweets were related to the analyzed topics.Overall, this analysis demonstrates how sentiment analysis can effectively capture public attitudes on social media. The results highlight the importance for 
brands and organizations to monitor online feedback, identify negative trends, and take data-driven actions to improve customer perception and engagement.

