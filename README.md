# Project Title: Content-Based-Movie-Recommendation-System

# Description:
This project is a Content-Based Movie Recommendation System implemented in Python using TF-IDF vectorization on movie genres. Given a movie title, it recommends similar movies based on genre similarity.

# Key Features:

-> Uses movie genres to compute similarity between movies.

-> Recommends top 5 movies similar to a given movie.

-> Built using Python, pandas, and scikit-learn.

-> Easy to extend with additional content features (like plot, keywords, actors).

# Dataset

The project uses a movies.csv file containing the following columns:

| Column  | Description              |
| ------- | ------------------------ |
| movieId | Unique ID for each movie |
| title   | Movie title              |
| genres  | Pipe-separated genres    |

# Technologies:
Python 3, pandas, scikit-learn (TF-IDF Vectorizer, cosine similarity)

# How it Works: 

1. TF-IDF Vectorization: Converts the genres of all movies into numerical vectors.

2. Cosine Similarity: Measures similarity between movies based on their genre vectors.

3. Recommendation Function: Finds the top 5 movies with the highest similarity to the input movie.
