# 🎬 Movie Recommender System

A Machine Learning based Movie Recommender System built using **Python, Pandas, Scikit-Learn and Streamlit**.
The system recommends similar movies based on the movie selected by the user.



# 🚀 Live Demo
https://movie-recommender-system-xejb3f6cyweiyccnszrxtm.streamlit.app/



# 📌 Features


• Recommend 5 similar movies instantly

• Movie posters fetched using TMDB API

• Interactive UI built with Streamlit

• Content-based filtering using cosine similarity

• Fast and simple recommendation system




# 🧠 How It Works

1. Movie dataset is preprocessed.
2. Important features like genres, keywords, cast and crew are combined.
3. Text data is converted into vectors using CountVectorizer.
4. Cosine similarity is calculated between movies.
5. Based on similarity scores, top 5 movies are recommended.



# 🛠 Tech Stack


Python

Pandas

NumPy

Scikit-Learn

Streamlit

TMDB API




# 📂 Project Structure

movie-recommender-system

│

├── app.py

├── movie_dict.pkl

├── movies.pkl

├── similarity.pkl

├── requirements.txt

└── README.md




# ⚙️ Installation

Clone the repository

git clone https://github.com/YOUR_USERNAME/movie-recommender-system.git

Go to project directory

cd movie-recommender-system

Install dependencies

pip install -r requirements.txt

Run the app

streamlit run app.py



# 🎥 Dataset

Dataset used: TMDB 5000 Movie Dataset

Includes:

* Movie titles
* Cast
* Crew
* Genres
* Keywords



# 📊 Machine Learning Concepts Used

Content Based Recommendation

Vectorization (CountVectorizer)

Cosine Similarity

Data Preprocessing




# 💡 Future Improvements

• Hybrid Recommendation System

• User login system

• Movie ratings integration

• Deploy on cloud



# 👩‍💻 Author

Kasak Bhatia

# ⭐ If you like this project

Give it a star on GitHub!
