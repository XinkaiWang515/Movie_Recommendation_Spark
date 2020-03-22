# Movie_Recommendation_Spark

In this project, I built a movie recommendation engine with alternative least square (ALS) model with Spark Python and SQL. In the Netflix movie rating data, there are more than 280K users give around 27.7M rating to 50K movies. All the work is in the notebook [movie-recommender-with-ES](https://github.com/XinkaiWang515/Movie_Recommendation_Spark/blob/master/movie-recommender-with-ES.ipynb).
  
  
## Here are some pictures used for analysis:
  
  
This picture on the **left side** illustrates the **average rating score for each category of movies**, while the **right** one shows the **rating number that each category received**.
  
<img align="center" src="https://github.com/XinkaiWang515/Movie_Recommendation_Spark/blob/master/rating_w_movie_categories.png" alt="rating for each category"/>.
  
### This is learning curve of training and validation for ALS model.  
  
<img align="center" src="https://github.com/XinkaiWang515/Movie_Recommendation_Spark/blob/master/learning_rate.png" alt="learning rate" width=500 height=400 />.
  
  
## Here are the pictures illustrate results of recommendation:  

### Recommend the most similar movies:    

<img align="center" src="https://github.com/XinkaiWang515/Movie_Recommendation_Spark/blob/master/similar_movies.png" alt="similar movies" width=500 height=400 />.  
  
  
### Recommend to specific user:    
  
  
<img align="center" src="https://github.com/XinkaiWang515/Movie_Recommendation_Spark/blob/master/rec_to_user.png" alt="recommend to specific user" width=500 height=400 />.
