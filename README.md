# 🎬 Movie Recommendation System

A Movie Recommendation System built using **Streamlit**, **FastAPI**, and the **TMDB API**. The application provides movie search, content-based recommendations using TF-IDF, genre-based recommendations, and real-time movie details with posters and ratings.

## 🚀 Features

- 🔍 Search movies by title
- 🎯 TF-IDF based movie recommendations
- 🎭 Genre-based recommendations
- 🖼️ Movie posters, ratings, and release dates
- ⚡ FastAPI REST API backend
- 🎨 Interactive Streamlit web interface

##Project Interface:
<img width="1899" height="954" alt="Screenshot 2026-08-07 231621" src="https://github.com/user-attachments/assets/28da21d1-7a5e-44e2-933b-857c965ff864" /><img width="1889" height="940" alt="Screenshot 2026-08-07 231638" src="https://github.com/user-attachments/assets/18680389-b110-4c39-9d7f-ed7b3b92939a" />
<img width="1904" height="965" alt="Screenshot 2026-08-07 231607" src="https://github.com/user-attachments/assets/009681c1-54e3-47a2-89f8-b2622ab40495" />



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
