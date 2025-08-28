🎬 Movie Recommendation System
(https://github.com/user-attachments/assets/002ab0f7-e9ab-48df-9f19-e65b29c2ce4d)
A content-based movie recommendation system that suggests movies similar to the one you like. It uses cosine similarity on movie metadata (genres and tags) to find the closest matches and displays additional details fetched via the OMDb API.
-: How It Works
Processes a dataset of movies containing titles, genres, and tags
Converts text data into numerical vectors using TF-IDF or CountVectorizer
Calculates cosine similarity to find movies most similar to user input
Uses OMDb API to fetch:
Movie posters
Ratings
Plot summaries
🌐 API Integration
The OMDb API enhances the recommendation system by providing dynamic movie details instead of relying only on local data. API calls are made for each recommended movie to display real-time information.
🎥 Demo
(Screen recording attached in the repository)
✨ Features
Interactive Streamlit UI
Accurate recommendations using content-based filtering
Real-time movie details via OMDb API
