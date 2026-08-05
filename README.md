# 🎬 Movie Recommendation System

A Movie Recommendation System built using **Streamlit**, **FastAPI**, and the **TMDB API**. The application provides movie search, content-based recommendations using TF-IDF, genre-based recommendations, and real-time movie details with posters and ratings.

## 🚀 Features

- 🔍 Search movies by title
- 🎯 TF-IDF based movie recommendations
- 🎭 Genre-based recommendations
- 🖼️ Movie posters, ratings, and release dates
- ⚡ FastAPI REST API backend
- 🎨 Interactive Streamlit web interface

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** FastAPI, Uvicorn
- **Machine Learning:** Scikit-learn (TF-IDF, Cosine Similarity)
- **Data Processing:** Pandas, NumPy
- **API:** TMDB API
- **Deployment:** Streamlit Community Cloud (Frontend), Render (Backend)

## ▶️ Installation

```bash
git clone https://github.com/aryanantad/Movie-Recommendation-System.git
cd Movie-Recommendation-System

python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Create a `.env` file:

```env
TMDB_API_KEY=YOUR_TMDB_API_KEY
```

Run locally:

```bash
# Backend
python -m uvicorn main:app --reload

# Frontend
streamlit run app.py
```
# to use Link:
https://movie-recommendation-system-i4szjt73hxcffshwjvxnm4.streamlit.app/

## 👨‍💻 Author

**Aryan Antad**  
B.Tech – Artificial Intelligence & Machine Learning

⭐ If you found this project useful, consider giving it a star on GitHub.
