Movie Recommendation System
This is a simple movie recommendation system that uses item-based and user-based collaborative filtering. The system is built using Python 3 and the pandas, numpy, and scikit-learn libraries.

Files
movies.csv: contains a list of movies and their metadata
ratings.csv: contains a list of user ratings for movies
tags.csv: contains a list of user tags for movies
Movie_Recommendation_System.ipynb: a Jupyter notebook that contains the code for the recommendation system
Item-based Collaborative Filtering
In item-based collaborative filtering, the system recommends movies that are similar to a user-selected movie based on the similarity of their user ratings. The system calculates the Pearson's correlation coefficient between the user ratings of the selected movie and all other movies in the dataset. It then recommends the movies with the highest correlation coefficients.

User-based Collaborative Filtering
In user-based collaborative filtering, the system recommends movies that were highly rated by users who have similar movie preferences to the user. The system calculates the cosine similarity between the user ratings of all users in the dataset. It then recommends the movies that were highly rated by the users with the highest cosine similarities.

Popularity-based Recommendations
In popularity-based recommendations, the system recommends movies that are popular among users based on their average ratings and the number of ratings they have received. The system calculates a popularity score for each movie and recommends the movies with the highest scores.
