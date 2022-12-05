# Spotify-recommendations

## Building a Song Recommendation System with Spotify:

This dataset is based on the subset of users in the #nowplaying dataset who publish their #nowplaying tweets via Spotify.
In principle, the dataset holds users, their playlists and the tracks contained in these playlists.

Have downloaded this dataset from www.kaggle.com

## Introduction:

A recommendation system or recommendation engine is a model used for information filtering where it tries to predict the preferences of a user and provide suggests based on these preferences. These systems have become increasingly popular nowadays and are widely used today in areas such as movies, music, books, videos, clothing, restaurants, food, places and other utilities. These systems collect information about a user's preferences and behaviour, and then use this information to improve their suggestions in the future.
Spotify does a great job of recommending tracks via both daily mixes and track radios, but how do we build something like this ourselves? The aim here was to use machine learning and recommender system techniques to recommend new tracks based on tracks in my favourite playlists.

## Problem Statement:

This project’s goal is to provide automatic playlist continuation which would enable any music platform (here Spotify) to seamlessly support their users in creating and expanding the playlists by making recommendations based on their choices and preferences.
Also, developing a Spotify playlist builder with a songs recommender using k-means algorithm.

### Popularity Recommending systems:

A popularity recommender recommends songs ranked by their popularity regardless of user’s preferences. This is of course dependent upon the methodology used to determine the popularity metric (usually some function of time, user interactions, and user ratings).

### Collaborative filtering systems:

Analyse the user's behaviour and preferences and predict what they would like based on similarity with other users. There are two kinds of collaborative filtering systems.

### user-based recommender and item-based recommender:

User-based preferences are very common in the field of designing personalized systems. This approach is based on the user's likings. The process starts with users giving ratings (1-5) to some songs. These ratings can be implicit or explicit. Explicit ratings are when the user explicitly rates the item on some scale or indicates a thumbs-up/thumbs-down to the item.


### K-means:

Is a centroid-based clustering algorithm that follows a simple procedure of classifying a given dataset into a pre-determined number of clusters, denoted as “k”.
Building a Song Recommendation System with Spotify

## File descriptions:

spotify_dataset.csv - data set

## Structure:

* Data Import
* Exploratory Data Analysis
* Visualization
* Explore most played tracks, artists, playlists and their graph associations
* Recommendation engine
* Clustering
* Matrix Factorization
* Conclusion

## Result:
data:image/png;base64
