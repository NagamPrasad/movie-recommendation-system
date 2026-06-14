# Movie Recommendation System

A user-based collaborative filtering recommendation engine
built on the MovieLens 100K dataset.

## What it does
- Recommends top 5 movies to any user based on what
  similar users have rated highly
- Uses cosine similarity to find users with similar taste
- Filters out movies the user has already seen

## Results
- Dataset: 943 users, 1,682 movies, 100,000 ratings
- RMSE: 1.02 (replace with your score)
- Model: User-based collaborative filtering

## Tech stack
- Python, pandas, numpy, scikit-learn
- Google Colab

## How to run
1. Open Movie_Recommender.ipynb in Google Colab
2. Run all cells in order (Runtime → Run all)
3. Change user_id in the last cell to get recommendations

## Dataset
MovieLens 100K — https://grouplens.org/datasets/movielens/100k/

