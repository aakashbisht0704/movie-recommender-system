# Movie Recommender System

## Overview
This is a **Content-Based Movie Recommendation System** that suggests similar movies based on user input. It uses **vectorization and distance comparison** to find and recommend movies with similar characteristics. Users can **search or select a movie from the TMDB database** and receive the **top 5 most similar movies** as recommendations.

## Features
- **Content-Based Filtering:** Uses movie metadata for recommendations.
- **Vectorization & Similarity Comparison:** Converts movie data into vectors and computes distances to find similar movies.
- **TMDB Integration:** Users can search or select movies from the TMDB database.
- **Top 5 Recommendations:** Returns the most relevant movies based on content similarity.

## Technologies Used
- **Python** (for backend processing)
- **Scikit-learn** (for vectorization and similarity computation)
- **Pandas & NumPy** (for data processing)
- **Streamlit** (for web application)
- **TMDB API** (for movie search and details)

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/movie-recommender.git
   cd movie-recommender
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Application**
   ```sh
   streamlit run app.py
   ```

## Usage
1. **Search or Select a Movie** from the TMDB database.
2. **Receive Recommendations**: The system will return the top 5 most similar movies.

## Contributing
Feel free to contribute! Fork the repository and submit a pull request with your improvements.