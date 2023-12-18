# Recommendation System (Collaborative Filtering) for Book Crossings Dataset 
 Recommender System Implementation on Book Crossings Dataset

This project is an implementation of 3 types of computation on Collaborative Filtering (CF) for Recommendation System:
### 1. User-based Collaborative Filtering
### 2. Item-based Collaborative Filtering
### 3. Latent Factor Approach - Matrix Factorization

Write up explanation/logic/details for the 3 CF approaches is available at: https://writedsaistories.wixsite.com/writedsaistories/post/recommendation-systems

## Instructions
**Step 1:** Run the Create_all_ratings.ipynb to create all_ratings.csv (which is a merged dataset that contains information from the 3 datasets in raw_data folder: BX_Books.csv, BX-Book-Ratings.csv, BX-Users.csv

**Step 2:** Run any of the other notebooks to explore the recommendations produced by each approach 

## Notebooks Details

**RecSys_all_predict_ratings.ipynb** : is a summary notebook which consists an example of a predicted rating for a book which has not been read by a specified user, followed by the user-based CF, item-based CF and matrix factorization approaches respectively

**RecSys_UserBasedCF_predict_ratings** : implements the item-based CF for book recommendation
**RecSys_ItemBasedCF_predict_ratings** : implements the item-based CF for book recommendation
**RecSys_matrixfactorization_predict_ratings** : implements the latent factor approach - matrix factoirzation for book recommendation

## To do: 
- Further refactoring
- Attempt from-scratch implementation of CF approaches

## References: 
https://realpython.com/build-recommendation-engine-collaborative-filtering/ 
