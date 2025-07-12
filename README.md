# 🎬 Content-Based Movie Recommendation System using Python and real-world movie metadata

This project demonstrates the development of a **Content-Based Movie Recommendation System** using metadata such as movie rating and movie descriptions. This project is just a basic movie recommendation system build just for fun ad a data science project.

---

## 📌 Objective

To build a recommendation system that suggests movies similar to a given movie or given description by analyzing and comparing movie rating and movie description using cosine similarity.

---

## 📂 Dataset Description

We use two primary datasets:

1. **`movies_metadata.csv`**
   - Contains movie information: `movie_id`, `title`, `overview`, `vote_average`, `vote_count`.
   
2. **`ratings.csv`**
   - Contains user ratings: `user_id`, `movie_id`, `rating`.
   - Used here only for exploratory insight, not modeling.

---

## 🧹 Data Preprocessing

- Loaded and cleaned the metadata:
  - Handled missing values.
---

## 🔍 Feature Engineering

- Applied **cosine similarity** on the vectorized metadata to measure similarity between movies.

---

## 🤖 3 Recommendation Logic:

- Implemented three functions that:
  1)
  - Takes a movie title as input.
  - Returns the top 10 most similar movies based on cosine similarity.
    
  2)
  - Also takes a movie title as input.
  - Returns the top 10 most similar movies based on cosine similarity.
 
  3)
  - Also takes a movie description as input.
  - Returns the top 10 most similar movies based on cosine similarity.

Example:
> **Input**: *The Matrix*  
> **Recommendations**: *The Matrix Reloaded*, *The Matrix Revolutions*, *Inception*, *Equilibrium*, *Minority Report*, etc.

---

## ✅ Key Highlights

- Pure **content-based filtering**.
- Lightweight and interpretable recommendation engine.

---

## 📈 Possible Enhancements

- Add genre and release year filters to improve recommendation relevance.
- Introduce **TF-IDF vectorization** for longer text fields like overviews.
- Combine with user-based or collaborative filtering to build a hybrid model.

---

## 📚 Libraries Used

- `pandas`, `numpy`
- `sklearn.metrics.pairwise.cosine_similarity`

---

## 🙌 Author

**Aman Sagar**  
*Aspiring Data Scientist | ML Enthusiast | Lifelong Learner*

---
