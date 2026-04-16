# 🎬 Movie Recommendation System using K-Means Clustering

## 📌 Overview
This project builds a **content-based movie recommendation system** using K-Means clustering.  
Movies are grouped based on their features, and recommendations are made by selecting movies from the same cluster.

---

## 🎯 Problem Statement
With a large number of movies available on streaming platforms, users often struggle to find relevant content.  
This project uses clustering to group similar movies and recommend them without relying on user history.

---

## 🚀 Objectives
- Group similar movies using K-Means clustering  
- Identify patterns in movie data  
- Build a recommendation system based on clusters  
- Improve content discovery  

---

## 🧠 Approach

### 1. Data Preprocessing
- Selected important features: `rating`, `popularity`, `revenue_million`  
- Handled data cleaning  
- Applied feature scaling using StandardScaler  

### 2. Clustering
- Applied **K-Means algorithm**  
- Used **Elbow Method** to determine optimal clusters  
- Validated clusters using **Silhouette Score**  

### 3. Visualization
- Used **PCA (Principal Component Analysis)**  
- Reduced data to 2D for visualization  
- Plotted clusters using Matplotlib  

### 4. Recommendation System
- Identified cluster of selected movie  
- Recommended movies from the same cluster  

---

## 📊 Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📂 Dataset
- Custom-generated dataset with 900 movies  
- Features include:
  - Title  
  - Genre  
  - Rating  
  - Popularity  
  - Duration  
  - Revenue  

---

## 📈 Results
- Successfully segmented movies into meaningful clusters:
  - 🎬 Blockbuster movies  
  - 🎭 Average movies  
  - 😬 Low-performing movies  
- Achieved improved clustering performance  
- Built a working recommendation system  

---

## 🎬 Sample Code

```python
def recommend(movie_name):
    movie = df[df['title'] == movie_name]
    
    if movie.empty:
        return "Movie not found"
    
    cluster = movie['cluster'].values[0]
    
    recommendations = df[df['cluster'] == cluster]
    
    return recommendations['title'].head(10)
