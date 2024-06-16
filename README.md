DU-VIRT-AI-PT-05-2024-U-LOLC-MWTH - Module 6 Challenge (June 15, 2024)

# Module 6 Challenge - Data Sourcing: Movie Recommendation System

[retrieve_movie_data.ipynb](https://github.com/JimGile/data-sourcing-challenge/blob/main/retrieve_movie_data.ipynb)

## Focus

Module 6 focuses on the art of data sourcing for AI. These skills will be used to source and manage data effectively, laying a solid foundation for impactful AI projects.

Topics covered:

* Licensing agreements
* Extracting data from online sources (HTML tables)
* Application Programming Interfaces (APIs):
  * Access APIs with keys
  * Set up environment variables
* Exception handling:
  * try and except clauses
* Software Development Kits (SDK's)
* Create Python applications using APIs.

## Challenge

Prepare data for a recommendation system to help people find movie reviews and related movies. Extract data from two different sources, The New York Times API and The Movie Database, then merge the data together. The text extracted from these APIs can later be used with natural language processing methods.

The Challenge has three parts:

* Part 1: Access the New York Times API.
* Part 2: Access The Movie Database API.
* Part 3: Merge and Clean the Data for Export.

## Solution

* Jupyter Notebook file: [retrieve_movie_data.ipynb](https://github.com/JimGile/data-sourcing-challenge/blob/main/retrieve_movie_data.ipynb).
* Output file: [tmdb_nyt_movie_reviews.csv](https://github.com/JimGile/data-sourcing-challenge/blob/main/output/tmdb_nyt_movie_reviews.csv).
* NOTE: These two csv files were saved off so that I didn't have to run the API's every time.
  * [reviews_df.csv](https://github.com/JimGile/data-sourcing-challenge/blob/main/output/reviews_df.csv)
  * [tmdb_movies_list_df.csv](https://github.com/JimGile/data-sourcing-challenge/blob/main/output/tmdb_movies_list_df.csv)

## References

* [NYT Article Search "Try this API"](https://developer.nytimes.com/docs/articlesearch-product/1/routes/articlesearch.json/get)
* [TMDB Search Documentation](https://developer.themoviedb.org/docs/search-and-query-for-details)
