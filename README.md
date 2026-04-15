# movielens

# 🎬 Movie Recommendation System

A content-based movie recommendation system built using the MovieLens dataset.
This project suggests similar movies based on genres, titles, and user-generated tags, with ranking improved using rating quality and popularity.

---

## 📌 Project Overview

Recommendation systems are widely used in platforms like Netflix and Amazon to improve user experience.

In this project, I built a **content-based recommender system** that:

* analyzes movie metadata (title, genres, tags)
* computes similarity between movies
* ranks results using both similarity and popularity

---

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Engineer meaningful features from raw data
* Build a content-based recommendation model
* Improve recommendations using weighted rating and popularity
* Deliver a clean, portfolio-ready ML project

---

## 📂 Dataset

This project uses the:

* MovieLens Latest Small Dataset

Files used:

* `movies.csv`
* `ratings.csv`
* `tags.csv`

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

---

## 🧠 Methodology

### 1. Data Processing

* Cleaned missing values
* Extracted movie release year
* Aggregated user-generated tags

### 2. Feature Engineering

* Number of ratings (popularity)
* Average rating (quality)
* Weighted rating (IMDb-style)
* Combined text features (title + genres + tags)

### 3. Modeling

* TF-IDF vectorization of text features
* Cosine similarity to measure movie similarity

### 4. Ranking Strategy

Final recommendations are ranked using:

* similarity score
* weighted rating
* number of ratings

---

## 🔍 Example

Input:

```python
print_recommendations("Toy Story (1995)")
```

Output:

```
If you liked 'Toy Story (1995)', you might also like:

1. Toy Story 2 (1999)
2. A Bug's Life (1998)
3. Monsters, Inc. (2001)
...
```

---

## 📊 Results

* Produces relevant movie recommendations based on content similarity
* Filters out low-quality or unpopular movies
* Combines similarity with real-world usefulness

---

## 🚧 Limitations

* Does not use collaborative filtering
* No user-personalized recommendations
* Limited to available metadata

---

## 🔮 Future Improvements

* Add collaborative filtering (user-based or matrix factorization)
* Use movie descriptions (NLP embeddings)
* Build hybrid recommendation system
* Deploy with Streamlit
* Integrate external APIs (e.g., TMDB)

---

## 📁 Project Structure

```
movie-recommender/
│
├── movies.csv
├── ratings.csv
├── tags.csv
├── movies_enriched.csv
├── notebook.ipynb
└── README.md
```

---

## 💡 Key Learnings

* Feature engineering is critical for recommendation systems
* Combining similarity with popularity improves real-world results
* Text vectorization (TF-IDF) is powerful for content-based filtering

---

## 👤 Author

Dmitry

---

## ⭐ If you found this useful

Feel free to ⭐ star the repo or connect!
