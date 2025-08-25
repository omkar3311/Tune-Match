# Tune-Match

## 🎶 Spotify Music Recommendation System (Clustering + PCA)

## 📌 Project Overview
This project builds a **content-based music recommendation system** using the Spotify dataset.  
By analyzing audio features such as **tempo, loudness, energy, and danceability**, we cluster songs into meaningful groups and recommend similar tracks.  

The system applies:
- **Principal Component Analysis (PCA)** → to reduce feature complexity.  
- **K-Means Clustering** → to group songs into "musical neighborhoods."  
- **Recommendation Engine** → suggests top-N similar songs from the same cluster.  

---

## 🚀 Features
- Clusters songs based on audio features.  
- Recommends similar songs without needing user history.  
- Solves the **cold-start problem** for new users or emerging artists.  
- Provides insights for playlist generation and music discovery.  

---

## 📊 Methodology
1. **Data Collection**: Spotify dataset from Kaggle.  
2. **Preprocessing**: Cleaned, normalized features.  
3. **Dimensionality Reduction**: Applied PCA to highlight key variance.  
4. **Clustering**: Used K-Means to group songs.  
5. **Recommendation**: Retrieved top-N songs from the same cluster.  
6. **Evaluation**: Achieved **Silhouette Score = 0.53**, indicating strong separation between musical groups.  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** → Data handling  
- **Scikit-learn** → PCA, K-Means, evaluation metrics  
- **Matplotlib / Seaborn** → Visualization  
- **Spotify Dataset (Kaggle)**  

---

## 🎯 Results
- Formed **well-defined clusters** of songs (e.g., upbeat dance vs. mellow acoustic).  
- Recommendation engine generates musically coherent suggestions.  
- Achieved **Silhouette Score: 0.53** → strong separation between clusters.  

---
## Author

Developed by **Omkar Waghmare**.  
Aspiring Data Scientist | Passion for ML & Data
