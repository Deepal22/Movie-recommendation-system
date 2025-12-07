🎬 Movie Recommendation System

This project is a Content-Based Movie Recommendation System built using Python, NLP, and machine learning techniques. It recommends movies similar to a user-selected movie by analyzing text features such as genres, cast, crew, keywords, and overview. The system uses Bag-of-Words vectorization, Cosine Similarity, and a simple Streamlit web interface to provide fast and meaningful recommendations.

🔍 Overview

The dataset is preprocessed by cleaning text, merging important movie features, and generating a tags column for each movie. These tags are vectorized using CountVectorizer, allowing the system to calculate similarity scores between all movies. The engine retrieves the top recommended movies based on these similarity scores, making it effective for academic and practical applications.

🚀 Features

Content-based recommendation using NLP

Tags created from multiple movie attributes

Bag-of-Words vectorization

Cosine similarity for ranking

Streamlit-based interactive UI

Easy to deploy on cloud platforms

🖼️ Screenshots

You can add screenshots of your project for better presentation. Use the format below:

Home Page Screenshot
<img width="1919" height="898" alt="Screenshot 2025-11-27 123650" src="https://github.com/user-attachments/assets/0c0a0a4d-7b57-4759-8e07-cd4b2f48a759" />

Recommendation Output Screenshot
<img width="1919" height="908" alt="Screenshot 2025-11-27 123819" src="https://github.com/user-attachments/assets/4d437bfb-702f-4e0e-8bd1-6a09402536a1" />


Screenshots help viewers understand how the interface looks and how the recommendation results are displayed.

🌐 Live Demo URL

If your project is deployed Render. Live link here:

Live Application:
(https://movie-recommendation-system-3-mopy.onrender.com)

This allows users to try the recommendation system without downloading the project.

📂 Project Workflow

Data preprocessing and feature cleaning

Creating combined tags for each movie

Vectorizing tags using CountVectorizer

Computing movie-to-movie similarity

Displaying recommendations with Streamlit UI

🖥️ Running the Project

Install required dependencies:
pip install pandas numpy scikit-learn nltk streamlit

Run the app:
streamlit run app.py

📌 Future Scope

Add TF-IDF for improved vectorization

Integrate movie posters via TMDB API

Combine collaborative filtering + content-based approach

Improve UI/UX and add search functionality

📄 Conclusion

This Movie Recommendation System is a compact, effective, and educational project demonstrating real-world NLP and machine learning workflows. With clean preprocessing, vectorization, similarity computation, and a deployable interface, it serves as a valuable tool for learning, academic submissions, and portfolio building.
