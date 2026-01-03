🎬 Movie Recommender System

A content-based movie recommendation system built using Python, Machine Learning, and Streamlit.
The application recommends similar movies based on movie metadata such as genres, keywords, cast, and overview.

🔗 Live Demo: (add Streamlit Cloud link if available)
📌 Portfolio Project for LinkedIn & Resume

🚀 Features

🔍 Select a movie and get top 5 similar movie recommendations

🧠 Uses cosine similarity on processed movie features

🎨 Clean and interactive Streamlit UI

🖼️ Movie posters displayed for better visual experience

⚡ Fast recommendations using precomputed similarity matrix
movie-recommender-system/
│
├── app.py                 # Streamlit application
├── movies.pkl             # Processed movie metadata
├── requirements.txt       # Dependencies
├── posters/               # Local movie poster images (for demo)
│   ├── avatar.jpg
│   ├── aliens.jpg
│   ├── titanae.jpg
│   └── default.jpg
└── README.md
🧠 How It Works

Movie metadata is preprocessed and vectorized

Cosine similarity is calculated between movies

When a user selects a movie:

The most similar movies are retrieved

Corresponding posters are displayed

Results are shown instantly on the UI
