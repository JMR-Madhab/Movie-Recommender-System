# 🎬 Movie Recommender System

A **Movie Recommender Web App** built with **Content-Based Filtering** that suggests movies similar to the one selected by the user.  
This project uses a pre-computed similarity matrix and movie metadata to generate recommendations. The frontend is built using **Streamlit**.

## 🚀 Features
- Interactive **Streamlit web app**.
- Recommends **5 similar movies** based on the selected movie.
- Fetches and displays **movie posters** using the **TMDB API**.
- Uses **pickle-serialized models** (`movie_list.pkl` & `similarity.pkl`) for fast recommendations.

## 🛠️ Tech Stack
- **Python 3**
- **Streamlit**
- **Requests**
- **Pickle**
- **Pandas / Scikit-learn** (used during model building)

## 📂 Project Structure
- app.py # Streamlit app for recommendations
- movie-recommender-system.ipynb # Jupyter Notebook (model building & similarity matrix)
- model/
- - movie_list.pkl # Serialized movie metadata
  - similarity.pkl # Precomputed similarity matrix
- README.md # Project documentation

  
