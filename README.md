# Movie-Recommendation-System

This is a simple movie recommender system that suggests similar movies based on a selected title.

### What I Did

- Collected and processed movie data from the [TMDB Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) on Kaggle.
- Built a content-based recommendation model using cosine similarity.
- Created a web app using Streamlit to:
  - Select a movie
  - Show 5 similar movie recommendations
  - Display their posters using the TMDB API

The model and similarity matrix were built in the Jupyter notebook (`Notebook.ipynb`) and saved for use in the app (`app.py`).
