🎬 Movie Recommendation System | Content-Based Filtering
This project is a Movie Recommendation System built with Python and Streamlit that recommends similar movies based on their content (genres, keywords, overview, etc.). It uses Natural Language Processing (NLP) techniques and cosine similarity to find and suggest movies similar to the one selected by the user.

🚀 Features
🧠 Content-Based Movie Recommendations using cosine similarity
🎥 Fetches live movie posters from TMDb API
💡 Simple and interactive web UI built using Streamlit
📈 Recommends top 5 most similar movies
🗂 Movie data sourced from TMDb dataset

📂 Dataset
tmdb_5000_movies.csv – movie metadata (overview, genres, keywords, etc.)
tmdb_5000_credits.csv – crew and cast info
You can download the dataset from Kaggle TMDb Dataset.

🧠 Recommendation Logic
Preprocessing:
Merge cast, crew, keywords, and genres
Clean and normalize text using NLP techniques

Vectorization:
Convert text data into numerical format using CountVectorizer

Similarity:
Calculate cosine similarity between all movie vectors

Recommendation:
When a user selects a movie, return the top 5 most similar movies

🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
NLTK (or custom NLP)
Streamlit (for UI)
TMDb API (for posters)

▶️ How to Run
Clone the repository


git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
Install dependencies


pip install -r requirements.txt
Run the Streamlit app
streamlit run app.py

🔑 TMDb API Key
You need an API key from TMDb to fetch posters. Replace the placeholder in your code:0bf0835cedf5909d8bf3fb17b97ce869

📌 Future Improvements
Use TF-IDF or word embeddings for better recommendations
Add collaborative filtering
Improve UI with more filters (e.g., by year, rating)
Add genre-based filtering or search

📸 Sample Output
Recommending similar movies to “Spectre”:
Quantum of Solace
Never Say Never Again
Skyfall
From Russia with Love
Thunderball
<img width="1918" height="893" alt="image" src="https://github.com/user-attachments/assets/9d207375-fc02-49fd-a637-49052613066f" />

When a user selects a movie, return the top 5 most similar movies

