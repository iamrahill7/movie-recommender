# Movie Recommendation System with Sentiment Analysis

This repository contains a movie recommendation system integrated with sentiment analysis for user reviews. The system suggests movies based on user input and provides sentiment analysis for IMDb reviews.

## Dataset Sources

### IMDb 5000 Movie Dataset
The IMDb 5000 Movie Dataset includes information about 5000 movies scraped from IMDb, covering various aspects such as budget, genres, and user reviews.

- [IMDb 5000 Movie Dataset on Kaggle](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset/data)

### The Movies Dataset
The Movies Dataset contains metadata for 45,000 movies from TMDb (The Movie Database), including user ratings, genres, and cast information.

- [The Movies Dataset on Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

## How to Get the API Key?
1. **Create an Account:** Sign up on The Movie Database (TMDb) website.
   
2. **Request API Key:** Navigate to the API section in your account settings on TMDb. Fill out the required details to apply for an API key. If asked for a website URL, you can input "NA" if not applicable. Once approved, you will find your API key in the API sidebar of your account.

## Understanding Similarity Score and Cosine Similarity

### Similarity Score
- **Definition:** It is a numerical value between 0 and 1 that indicates how similar two items are based on their text details.

### Cosine Similarity
- **Functionality:** Measures the cosine of the angle between two vectors in a multi-dimensional space.
- **Advantage:** Useful for determining similarity between documents regardless of their size, emphasizing orientation rather than distance.

These measures help in efficiently recommending items (such as movies) by quantifying their textual similarity using mathematical metrics like cosine similarity.

