# US-YouTube-Trending-Videos-Analysis

## Introduction
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). In this project, we cleaned US YouTube trending videos data and used Python packages such as numpy, pandas, and seaborn to analyze it in order to address some questions. For example, are there any relationships between views and likes/dislikes/comments? What are some most frequent appeared words in video titles? And are there any relationships between title lengths and number of views/likes/dislikes/comments?

## Languages and Libraries
- <b>Language and platform</b>: Python 3, Jupyter Notebook
- <b>Libraries</b>: pandas, numpy, seaborn, matplotlib, datetime, wordcloud, collections

## Data Sources
In this project, we use the Trending YouTube Video Statistics for U.S. dataset from Kaggle. The dataset can be found at https://www.kaggle.com/datasnaek/youtube-new.

Since the dataset exceeds 25MB and is zipped, one should extract the file before running the code.

## Contents

By analysing the data, we want to address the following questions:

- Which category has the largest number of trending videos?
- Which category has the largest number of total views/likes/dislikes/comments?
- How many views, likes, dislikes, and comments do our trending videos have? Do videos with larger number of views also have larger number of likes, dislikes and comments? Are there any relationships between views and likes/dislikes/comments?
- What are the top 10 Viewed/Liked/Disliked/Commented Videos?
- Which YouTube channel has the largest number of trending videos?
- What's the title lengths of the trending videos? Are there any relationships between title lengths and number of views/likes/dislikes/comments?
- What are some most frequent appeared words in video titles? What are some most frequent appeared words in video tags?
- When were trending videos pubulished? What years? What months? On which days of the week? Are there any differences between number of videos published in weekdays and weekends? At which times of the day? Did authors have any specific times that they would like to publish?
- How much time passed between the videos published and trending?
- What proportion of videos prevent users from commenting? What proportion of videos prevent users from rating?
