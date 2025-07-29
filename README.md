# Movie Recommendation System
This project is a content-based movie recommendation system built using Python and deployed with Streamlit. It allows users to select a movie and get five similar movie recommendations along with their posters using the TMDB API.

## Features
Content-based filtering using cosine similarity

TMDB API integration to fetch movie posters

Interactive user interface built with Streamlit

Scrollable sidebar displaying the list of available movies

Lightweight and fast using pre-processed data stored with Pickle

## How It Works
A movie is selected from the dropdown menu.

The similarity matrix compares the selected movie to others based on metadata.

The top 5 most similar movies are identified.

Posters are fetched using the TMDB API.

Recommendations are displayed with titles and images.

## Technologies Used
Python

Pandas

scikit-learn

Streamlit

TMDB API

Pickle

## Setup Instructions
### Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/movie-recommendation-system.git
Navigate to the project directory:

bash
Copy
Edit
cd movie-recommendation-system
Create and activate a virtual environment:

rust
Copy
Edit
python -m venv .venv
.venv\Scripts\activate      (for Windows)
Install the required packages:

nginx
Copy
Edit
pip install -r requirements.txt
### Run the application:

arduino
Copy
Edit
streamlit run app.py
Data
The movie data is preprocessed and stored as a pickle file (movie_dict.pkl). The similarity matrix is also stored as a pickle file (similarity.pkl).

## API
This project uses the TMDB API to fetch movie posters. You will need an API key from TMDB and can insert it into the fetch_poster() function.
