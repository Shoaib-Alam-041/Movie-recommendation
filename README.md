# 🎬 Movie Recommendation System

This is a simple **Movie Recommendation System** built with Python. It uses **cosine similarity** to recommend movies similar to the one the user enters. The system compares the content-based features of movies (like genres, keywords, etc.) and suggests the top 10 most similar titles.

---

## 🚀 Features

- Takes a movie name as input from the user
- Finds the closest match using fuzzy string matching
- Uses **cosine similarity** to calculate similarity between movies
- Recommends the top 10 most similar movies
- Easy to run and extend with new data or features

---

## 🧠 Technologies Used

- Python
- Pandas
- scikit-learn
- difflib
- Cosine Similarity (via `sklearn.metrics.pairwise.cosine_similarity`)

---

## 📁 Dataset

The dataset should include:
- Movie titles
- Content-based features (e.g., genres, keywords, cast, director)
- An index column (used for similarity lookup)
