
Dataset link : https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset
IMPORTANT: Ensure the dataset is extracted directly into the repository directory. Note: All CSV files must reside in the same folder as the notebooks.

# Flow
1. Execute Matrix_factorization_and_cosine_similarity.ipynb to generate recommendations using matrix factorization and cosine similarity.
2. Execute KNN.ipynb to train the KNN model and obtain recommendations from the model.

Implemented advanced recommendation algorithms and data analysis technique, including user-user collaborative filtering techniques as well as item-item collaborative filtering to optimize movie recommendations and enhance the user experience. In this project we will use user-user based collaborative filtering technique (Matrix Factorization and Cosine similarity) and Item-item based collaborative filtering (KNN) to predict recommendations to users.

Dataset used: The datasets describe ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies.

The evaluation using Mean Absolute Error (MAE) indicated a score of 0.6 for Matrix Factorization, suggesting reasonable predicted ratings. Further analysis with Multiple Choice Error (MCE) graphs can confirm if any model outputs outliers. Ultimately, all three models offered sensible recommendations with some flexibility for customization.
