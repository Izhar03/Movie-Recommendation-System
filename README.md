
# Movie Recommendation System

Movie Recommendation System using Machine Learning and Content-Based Filtering (CBF)

## Overview
Welcome to the Movie Recommendation System project! This project aims to create a personalized movie recommendation system using machine learning techniques and content-based filtering (CBF). The system is designed to suggest movies to users based on their preferences and past movie interactions.

## Dataset
For this project, we have utilized the TMDB (The Movie Database) dataset, which consists of information about thousands of movies, including their titles, genres, plots, release dates, ratings, and more. The dataset contains 5000 movies, which will be used to train and test our recommendation system.

## Technologies Used
### Python:
 We have implemented the recommendation system using Python as the primary programming language.
Machine Learning: Various machine learning algorithms and techniques have been employed to create the movie recommendation model.
### Vectorization: 
Text vectorization techniques have been utilized to process textual data, such as movie tags and genres, into numerical representations suitable for machine learning algorithms.
### Content-Based Filtering (CBF): 
The recommendation system utilizes CBF to suggest movies based on the content features of previously watched or liked movies.

## How it Works

The Movie Recommendation System follows these steps:

### Data Preprocessing:
The TMDB dataset is preprocessed to handle missing values and irrelevant features. Textual data, such as movie plots and genres, is transformed into numerical representations using vectorization techniques.

### Content-Based Filtering (CBF):
We utilize CBF to create a movie profile for each user based on the movies they have previously watched or rated highly. The system identifies the key features (genres, actors, directors, etc.) that represent the user's preferences.

### Machine Learning Model:
We can employ various machine learning algorithms, such as k-Nearest Neighbors (k-NN) or cosine similarity, to find similar movies based on the user's movie profile. In our project we used the " cosine similarity " algorithms.

### Recommendation Generation:
Once the most similar movies are identified, the system generates a list of top 5 movie recommendations for the user.

## Contribution
We welcome contributions to improve the Movie Recommendation System. If you find any bugs or have ideas for enhancements, please create a pull request or open an issue on our GitHub repository.
