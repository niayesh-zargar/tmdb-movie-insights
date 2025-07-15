# 🎬 TMDb Movie Dataset Analysis

This project explores and analyzes the TMDb movie metadata to extract meaningful insights from budget, revenue, genres, and other key features of over 5,000 movies. It's a beginner-friendly data science project focused on real-world data cleaning, visualization, and basic exploratory analysis.

---

## 📁 Dataset
The dataset is sourced from [Kaggle - TMDb 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) and contains:
- `tmdb_5000_movies.csv`: Metadata of movies (title, budget, revenue, etc.)
- `tmdb_5000_credits.csv`: Credits info (cast and crew)

---

## 📊 Key Objectives
- Clean and merge the movie and credit datasets
- Convert JSON-formatted columns (e.g., genres, cast)
- Extract and analyze:
  - Most common genres
  - Top directors by number of films
  - Budget vs revenue relationships
  - Movie trends over years

---

## 📌 Tools & Libraries
- Python (Pandas, NumPy)
- Seaborn & Matplotlib for data visualization
- Jupyter Notebook

---

## 📈 Example Visuals
- 📊 Countplot: Number of movies per release year  
- 🎬 Bar Chart: Most frequent genres  
- 💰 Scatter Plot: Budget vs Revenue  
- 🎞️ Horizontal Bar: Top 10 directors

---

## 🚀 Future Work
This project can be extended to build predictive models (e.g., predicting movie success or rating).

---

## 📂 Project Structure
```
tmdb-movie-insights/
├── datasets/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
├── tmdb_analysis.ipynb
├── README.md
```

---


