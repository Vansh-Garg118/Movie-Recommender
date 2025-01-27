# 🎥 Movie-Recommender

This project implements a **Collaborative Filtering-based Recommendation System** using the MovieLens dataset. It preprocesses the data, applies normalization and feature engineering, and builds a recommender system to suggest movies based on user preferences.

---

## 🚀 Project Structure

### Preprocessing
- **Import libraries and load datasets.**
- **Genre Encoding:** Split and encode genres using one-hot encoding.
- **Rating Normalization:** Normalize ratings and convert timestamps to datetime.
- **Data Filtering:** Filter out movies with insufficient ratings.

### Model Building
- Create user-item interaction matrices.
- Apply **collaborative filtering techniques** using Singular Value Decomposition (SVD).

### Evaluation
- Compute **Root Mean Square Error (RMSE)** for validation.
- Recommend movies to users based on predicted ratings.

---

## 📚 Dataset
The system utilizes the [MovieLens 32M Dataset](https://grouplens.org/datasets/movielens/32m/), which includes:
- **Ratings:** User ratings for movies.
- **Movies:** Metadata about movies, including genres.
- **Tags:** User-provided tags for movies.
- **Links:** Links to IMDb and TMDb webpages.


