# 🎥 Movie Recommendation System

This project implements a **content-based Movie Recommendation System** using the **TMDB dataset**.  
Given a selected movie, the system recommends the **top 5 most similar movies** by applying **cosine similarity** on feature vectors derived from movie metadata.  

---

## 📌 Features

- **Content-Based Filtering**: Recommends movies similar to the one chosen by the user.  
- **Cosine Similarity**: Measures similarity between movies based on metadata features.  
- **TMDB Dataset**: Rich dataset containing titles, genres, keywords, and other metadata.  
- **Interactive Notebooks**: Jupyter Notebook implementation for experimentation.  

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Development Tools**: Jupyter Notebook, PyCharm  
- **Libraries**:  
  - Data Handling: Pandas, NumPy  
  - Machine Learning: Scikit-learn (cosine similarity)  
  - Visualization: Matplotlib, Seaborn  

---
---

## 🚀 How It Works

1. **Data Preprocessing** – Load and clean TMDB dataset.  
2. **Feature Extraction** – Select features such as genres, keywords, and overview.  
3. **Vectorization** – Convert textual features into vectors (CountVectorizer/TF-IDF).  
4. **Similarity Computation** – Apply **cosine similarity** to measure closeness between movies.  
5. **Recommendations** – For a given movie, return the top 5 most similar titles.  

---

## 📈 Results & Insights

- Provides **relevant and accurate movie suggestions** based on metadata.  
- Demonstrates the power of **cosine similarity for recommendation tasks**.  
- Easily extendable to other domains (songs, products, books).  

---

## 🎯 Learning Outcomes

- Practical experience with **content-based recommendation systems**.  
- Hands-on implementation of **cosine similarity and feature engineering**.  
- Skills in **data preprocessing, vectorization, and ML pipeline building**.  

---

## 🔮 Future Enhancements

- Add **collaborative filtering** and hybrid recommendation approaches.  
- Build a **Streamlit app** for interactive movie recommendations.  
- Integrate **deep learning models** (e.g., embeddings, autoencoders).  

---
