# Spotify-Recommender-System
This repository contains a Python script that analyzes the Spotify Music Dataset. The dataset consists of various attributes of songs such as acousticness, danceability, energy, instrumentalness, loudness, popularity, and more.

# Dataset
The dataset used in this analysis is stored in the spotify.csv file. It contains information about 174,389 songs, including their features and metadata. The columns in the dataset include:

* acousticness: The acousticness of the song.
* artists: The artists who performed the song.
* danceability: The danceability score of the song.
* duration_ms: The duration of the song in milliseconds.
* energy: The energy level of the song.
* explicit: Indicates whether the song contains explicit content (1) or not (0).
* id: The unique identifier of the song.
* instrumentalness: The instrumentalness of the song.
* key: The key of the song.
* liveness: The liveness score of the song.
* loudness: The loudness level of the song.
* mode: The mode of the song (major - 1, minor - 0).
* name: The name/title of the song.
* popularity: The popularity score of the song.
* release_date: The release date of the song.
* speechiness: The speechiness score of the song.
* tempo: The tempo (beats per minute) of the song.
* valence: The valence score of the song.
* year: The year the song was released.
# Data Analysis
The Python script  performs various operations on the dataset to gain insights and provide recommendations. Here's a summary of what the script does:

* Data Processing: The script performs data processing tasks such as dropping unnecessary columns and normalizing numeric columns using the Min-Max Scaler.

* Clustering: The script utilizes the K-means clustering algorithm to group songs based on their attributes. This allows for the differentiation of songs from different categories.

* Recommendation System: The script implements a recommendation system that suggests songs similar to a given input song. It calculates the Manhattan distance between songs based on their attributes and returns the top recommendations.

# Usage
To run the analysis, make sure you have the necessary Python libraries installed. Run the script, which will load the dataset, perform data processing and analysis, and provide recommendations based on user input.


# Acknowledgments
The Spotify Music Dataset used in this analysis is sourced from Kaggle. Special thanks to the dataset contributors for making it available for analysis.

