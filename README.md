# Movie Recommendation System

## Project Overview
This project builds a simple Movie Recommendation System using collaborative filtering based on user ratings. It analyzes user preferences and recommends movies similar to those the user has liked before by computing cosine similarity between movie rating vectors.

## Dataset
The project uses the MovieLens dataset, consisting of:

- `movies.csv`: Contains movie IDs and titles.
- `ratings.csv`: Contains user ratings for movies.

These datasets are used to create user-item matrices for recommendation.

## Features
- Data loading and preprocessing of MovieLens data.
- Exploratory data analysis (EDA) with visualizations using Matplotlib and Seaborn.
- Construction of a movie similarity matrix using cosine similarity.
- Functionality to recommend movies based on similarity scores.
- Visualization of ratings distribution and most rated movies.

## Tools and Libraries
- Python 3.x
- Pandas for data manipulation
- NumPy for numerical computations
- Scikit-learn for cosine similarity calculations
- Matplotlib and Seaborn for data visualization

## How to Run
1. Clone or download this repository.
2. Download the dataset CSV files (`movies.csv` and `ratings.csv`) from [MovieLens Dataset](https://grouplens.org/datasets/movielens/) or the Kaggle dataset.
3. Place these CSV files inside the `data/` folder.
4. Install the required Python packages by running:
   ```bash
   pip install -r requirements.txt
