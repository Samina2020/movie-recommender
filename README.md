Recommendation System with Vibe Coding
Description:

This project focuses on building a movie recommendation system using the CiaoDVD dataset. The goal is to apply different recommendation methods to estimate how users would rate movies based on available data.

Dataset:

The dataset includes numerical user interactions with movies. Each entry represents a rating given by a user to a specific movie. The key fields used in this project are:

userId – identifies each user
movieId – identifies each movie
rating – the score given by the user (on a scale)
Models Used:
Global Average approach
User-based prediction model
Evaluation Metrics:

To measure performance, the models were tested using:

RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)

The user-based model produced lower error values, indicating better prediction accuracy.

Tools & Technologies:
Python
Pandas
NumPy
Scikit-learn
Matplotlib
How to Run:
Open the notebook using Jupyter Notebook or Google Colab
Execute all cells in order to reproduce results
