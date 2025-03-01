# RecommenderSystem
Movie Recommender System

There are 3 types of Recommender System -
1. Content Based Recommender System - Recommendation based on tags.
2. Collabarative Recommender System - Recommending a movie based on simillar likes of people.
3. Hybrid

We will be using Content based Recommender system.

**Data FLow -
Data -> Preprocessing -> Model Building -> Converting to Website

Steps -
1. Data Fetching
2. Data cleaning
3. Dimensionality Reduction
4. TRansformation of Data from dictionary to list (Genre , Overview , keywords , Cast - only first 3 actors/actress , Crew - Only director)
5. Combining all the relevant columns into a single column tags
6. Convert a list into string
7. Stemming (to remove similar words)
8. Use of Bag of words to create vectors
9. Using cosine distance (As Euclidean distance does not provide correct results for higher dimensions. Here we have 5000 dimensions)
10. distance is inversely proportinal to simillarity
11. install pickle
12. Create 2 .pkl files for new_df and similarity dataframe

Refer Kaggle dataset - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv
<img width="1437" alt="image" src="https://github.com/SamruddhiBhosale/RecommenderSystem/assets/41594930/9b49c803-c15c-4af4-a3c4-7f694499277d">
