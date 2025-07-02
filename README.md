# 🎧 Spotify Music Recommendation System

A Flask-based web application that recommends similar songs using KMeans clustering and PCA, powered by Spotify audio features.

---

## 🧠 How It Works

- Uses **Spotify audio features** like danceability, energy, tempo, etc.
- Applies **KMeans clustering** to group similar tracks
- Reduces dimensionality using **PCA** for visualization
- Accepts a song input and returns 5 similar songs from the same cluster

---
## 🔧 Installation & Running

1. Clone the repository:
   ```bash
   git clone https://github.com/Abhishek01112002/spotify-music-recommender.git
   cd spotify-music-recommender
2.Install dependencies:
```
   pip install -r requirements.txt
```
3.Run the Flask app:
```
   python app.py
```
4. Visit: http://localhost:5000 in your browser


📸 Screenshots
![image](https://github.com/user-attachments/assets/01835738-a210-4799-847b-f659c12f2726)
