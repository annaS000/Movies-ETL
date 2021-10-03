# **Movies ETL**
## **Overview**
> This project demonstrates how to extract, transform, and load large datasets into a PostgreSQL database using Pandas, Numpy, JSON, and SQLAlchemy. Specifically, we are looking at the data for different movies from Wikipedia and Kaggle

---
## **Resources**
* The data from Wikipedia holds details about movies, such as budgets and box office returns, cast and crew, production and distribution, etc.
    * [Wikipedia data](https://github.com/annaS000/Movies-ETL/blob/main/resources/wikipedia-movies.json)
* The data from Kaggle is pulled from the MovieLens dataset which contains information for over 20 million reviews and details about the movies from [The Movie Database](https://www.themoviedb.org/)
    * [Kaggle metadata](https://github.com/annaS000/Movies-ETL/blob/main/resources/movies_metadata.csv)
    * [Kaggle ratings](https://github.com/annaS000/Movies-ETL/blob/main/resources/ratings.csv)

---

## **Deliverable 1**
Link to [Code](https://github.com/annaS000/Movies-ETL/blob/main/challenge/ETL_function_test.ipynb)

##### **wiki_movies_df**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/wikiD1.png?raw=true)

##### **kaggle_metadata**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/kaggleD1.png?raw=true)

##### **ratings**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/ratingsD1.png?raw=true)

---
## **Deliverable 2**
Link to [Code](https://github.com/annaS000/Movies-ETL/blob/main/challenge/ETL_clean_wiki_movies.ipynb)

##### **wiki_movies_df**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/wikiD2.png?raw=true)

##### **wiki_movies_df.columns.to_list()**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/colsD2.png?raw=true)

---
## **Deliverable 3**
Link to [Code](https://github.com/annaS000/Movies-ETL/blob/main/challenge/ETL_clean_kaggle_data.ipynb)

##### **wiki_movies_df**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/wikimoviesD3.png?raw=true)

##### **movies_with_ratings_df**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/wikiratingD3.png?raw=true)

##### **movies_df**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/moviesdfD3.png?raw=true)

---
## **Deliverable 4**
Link to [Code](https://github.com/annaS000/Movies-ETL/blob/main/challenge/ETL_create_database.ipynb)

##### **movies_query.png**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/movies_query.png?raw=true)

##### **ratings_query.png**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/ratings_query.png?raw=true)

##### **elapsed time**
![](https://github.com/annaS000/Movies-ETL/blob/main/resources/timedsqlD4.png?raw=true)