# DTSA-5510,  Final: Genre classification from song lyrics
### October 3, 2023

### Introduction
In this final project, I sought a theme related to my life or hobbies. Given that music is a perennial presence in my life, I explored topics related to it. I chose to work with a dataset that could aid in predicting music genres from song lyrics. Classification is a prevalent field in unsupervised learning.

### About Dataset

The dataset is sourced from Kaggle and is titled "Song Lyrics from 79 Musical Genres," accessible via the following link,

https://www.kaggle.com/datasets/neisse/scrapped-lyrics-from-6-genres/data

This dataset came from a desire for stretching my web scrapping skills as well as to trian a LSTM network to maybe compose some lyrics.

All the data were obtained by scraping the Brazilian website Vagalume using R.

There are two datasets artists-data.csv and lyrics-data.csv.

### Problem Definition
We aim to classify song genres based on their lyrics, utilizing the words and phrases unique to different artists. While this is fundamentally a supervised machine learning task, with many studies conducted using supervised or deep learning methods, our goal is different. We want to explore the potential of unsupervised learning for this task. Successfully creating a classification model without relying on labels offers significant advantages. It allows data scientists to utilize a broader variety of datasets in real-world applications without the need for labeled data.
