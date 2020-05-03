# MovieRatings
Final project for COGS 108 (Data Science in Practice)

Movies starring Will Smith, one of Hollywood's most prominent, haven't scored above a [70% on Rotten Tomatoes since 1998](https://www.unilad.co.uk/film-and-tv/will-smith-movies-havent-rated-above-70-on-rotten-tomatoes-since-1998/). 
Is this common for more movie stars?

Using a [Kaggle dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset),
we loaded cast info and IMDb scores for over 5000 popular Hollywood movies.

We first define:  
(Movie) IMDb score --> the actual score from 0 to 10 that IMDb critics rated a given movie  
Actor IMDb score --> averaging the IMDb scores of the movies a given actor had a lead in  
Cast IMDb score --> averaging the actor IMDb scores of the lead cast members of a given movie 

Using these ratings, we explored:
* The distribution of movie IMDb scores
* Actor IMDb scores for our favorite actors
* Actors with the highest and lowest actor IMDb scores
* The distributions of actor IMDb scores and cast IMDb scores
* Is there a correlation between actor IMDb scores and movie IMDb scores?
* Is there a correlation between cast IMDb scores and movie IMDb scores?
* Cast IMDb scores for movies with the highest IMDb scores v.s. IMDb scores for movies with the highest cast IMDb scores
* Cast IMDb scores for movies with the lowest IMDb scores v.s. IMDb scores for movies with the lowest cast IMDb scores
* Can we predict a movie's IMDb score from its cast IMDb score?
* Can we use actor IMDb scores to generate a dream cast resulting in the best movie IMDb score?
