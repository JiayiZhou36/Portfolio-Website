+++
title = "NLP YouTube category classification"
date = 2023-12-10
+++

### Introduction
The goal of this project is to classify the YouTube videos based on the tags of videos (a form of the descriptions for videos that enables users to search for content). It automates the categorization process so that it can improve the efficiency of categorization and potentially help advertisements targeting. Here is the link: [Project Link](https://github.com/JiayiZhou36/Fall2023_IDS703_FinalProject).

The data we’re using is from [Kaggle](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?select=US_youtube_trending_data.csv). It contains data from multiple countries, and we only selected the video records from the United States. Each row represents the tags for one specific video. One Video only belongs to one category. We’re specifically interested in whether the video belongs to music or sports category, which are the two major categories in the data. Each category has around 30,000 records.

The original dataset includes 16 columns and almost 30 categories. We only include the music and sports category. We removed the characters that are not in English characters or numbers to exclude other languages. We also converted the characters into lowercase. We tokenize our data into the form of lists of lists. Each record is a list including word as elements, and the lists of each record concatenate together as one large list. Finally, we stored the tokens of the two categories into separate txt files.

### Dataset
The original dataset we are using is from Kaggle (https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?select=US_youtube_trending_data.csv). We've cleaned the data into txt files for each category. Please load `category10.txt` and `category17.txt` as the real data. Pleae load `synthetic_music.txt` and `synthetic_sports.txt`when running the restults with synthetic data. 

### Libraries
Make sure to install the packages below:
`random`
`sklearn`
`time`
`torch`
`numpy`
`pandas`
`nltk` 
`typing`
`collections`