# 🎵 Spotify Song Clustering & Recommendation System

This project performs unsupervised clustering of Spotify songs based on their audio features and provides a recommendation system to suggest similar tracks. Using KMeans clustering and feature engineering, the system groups songs into distinct "vibe" clusters and allows users to get recommendations by simply entering a song title.

## 🚀 Features
- Clustering of songs using KMeans (Elbow method used to determine optimal clusters)
- Dimensionality reduction with PCA for visualization
- Content-based recommendation system based on audio features
- Interactive input: Enter a song name to receive similar song suggestions

## 📁 Dataset
The dataset contains audio features of thousands of Spotify songs with the following columns:
- `track_name`
- `artists`
- `popularity`
- `duration_ms`
- `explicit`
- `danceability`, `energy`, `tempo`, `liveness`, etc.
- `track_genre`

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🧠 Model Workflow
1. **Data Cleaning**: Handling missing and duplicate values
2. **Feature Engineering**: Encoding categorical features, dropping irrelevant columns
3. **Scaling**: Standardizing numeric features
4. **Clustering**: Using KMeans with optimal clusters found via Elbow method
5. **Recommendation**: Using cosine similarity within clusters to suggest similar songs


