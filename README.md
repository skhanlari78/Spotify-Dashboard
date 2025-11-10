# 🎵 Spotify Dashboard — Visual Analytics Project

**Course:** Visual Analytics — A.Y. 2024/2025  
**University:** Sapienza University of Rome  

---

## 📊 Overview
The **Spotify Dashboard** is an interactive visual analytics project that explores Spotify’s audio features using **Principal Component Analysis (PCA)** and **K-Means clustering**.  
It enables users to discover meaningful patterns, genre trends, and feature correlations in songs.

<p align="center">
  <img src="./Spotify Dashboard.jpg" alt="Spotify Dashboard Screenshot" width="85%">
</p>

---

## 🧠 Project Goals
- Visualize and explore Spotify’s audio features interactively  
- Discover patterns and clusters among songs  
- Analyze genre and artist popularity  
- Examine temporal trends in music data  

---

## 🧩 Dataset
The dataset combines:
- `high_popularity_spotify_data.csv`  
- `low_popularity_spotify_data.csv`

After merging and removing duplicates, the selected features include:  

> `energy`, `tempo`, `danceability`, `loudness`, `liveness`, `valence`, `speechiness`, `instrumentalness`, `mode`, `key`, `duration_ms`, `acousticness`

---

## ⚙️ Data Processing Workflow
1. **Preprocessing** – Remove duplicates, select audio features, standardize values  
2. **Dimensionality Reduction (PCA)** – Reduce dataset to 2 components  
3. **Clustering (K-Means)** – Identify optimal cluster number using the Elbow Method  
4. **Visualization** – Build an interactive dashboard to explore patterns  

---

## 💻 Tech Stack
| Purpose | Technologies |
|----------|---------------|
| **Data Processing** | Python, pandas, scikit-learn, matplotlib |
| **Visualization** | JavaScript, D3.js, HTML, CSS |
| **Interactivity** | Real-time filtering, hover effects, responsive layout |

---

## 📈 Dashboard Features
- 🟢 **Scatterplot** – PCA-based clusters with color-coded points  
- 💜 **Bar Chart** – Average audio feature values per cluster  
- 📅 **Date Interval Selector** – Filter songs by release date  
- 🎧 **Top 10 Genres / Artists / Tracks** – Ranked, filterable lists  
- 📊 **Dataset Overview Panel** – Quick statistics (e.g. avg. energy, valence, loudness)

---

## 🔍 Key Insights
- Clear separation between **upbeat** and **mellow** song clusters  
- Popularity spikes for **K-pop** and artists like *Bruno Mars* and *ROSÉ*  
- Strong **correlation between energy and loudness**  
- Dataset bias toward **recent releases (post-2015)**  
- Negative correlation between **acousticness** and **energy/loudness**

---