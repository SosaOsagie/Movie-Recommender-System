# Movie-Recommender-System
Movie Recommendation System with Collaborative Filtering and Cosine Similarity
This project presents two distinct approaches to Movie Recommender Systems, each catering to different preferences and environments.

Collaborative Filtering with Streamlit UI
The first implementation is a collaborative filtering Movie Recommender System built with Python and Streamlit. The user-friendly interface allows users to effortlessly select a movie from a dropdown menu and receive a curated list of recommendations. Noteworthy features include the display of movie posters alongside recommended titles, enhancing the overall user experience.

Features:
Collaborative Filtering: Recommendations are generated based on the similarity between movies, derived from a precomputed similarity matrix.
Streamlit UI: The interactive web-based interface is created using the Streamlit framework.
Movie Posters: The system dynamically fetches and showcases movie posters for a visually appealing recommendation display.
Data Source: Movie data is sourced from The Movie Database (TMDb)'s API.
Requirements and Setup:
Python 3.x
Streamlit
Requests
Instructions for Usage:
Set the working directory to the location of the pickled files containing movie data and the similarity matrix.
Run the script, launching the Streamlit app in a web browser.
Select a movie from the dropdown menu.
Click the "Show Recommendation" button to access a list of recommended movies.
Explore the recommended movies along with their corresponding posters.
Note:
Ensure that a valid API key for TMDb is available in the script for fetching movie details.

Cosine Similarity-Based Recommender in Jupyter Notebook
The second implementation employs Cosine Similarity in a Jupyter Notebook environment, offering a different perspective on movie recommendations.

Features:
Cosine Similarity: Recommendations are determined by calculating cosine similarity on vectorized movie data.
Jupyter Notebook: The system is designed to run seamlessly in a Jupyter Notebook environment.
Data Preparation: Movie data is loaded from CSV files (tmdb_5000_movies.csv and tmdb_5000_credits.csv) and then vectorized for cosine similarity calculation.
