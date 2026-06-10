# Movie Recommendation System using Content-Based Filtering

## Project Overview

This project implements a Content-Based Movie Recommendation System using the TMDB 5000 Movies Dataset.

The recommendation engine suggests movies similar to a selected movie by analyzing textual metadata such as genres, keywords, and movie descriptions.

The system uses Natural Language Processing (NLP) techniques and Cosine Similarity to identify movies with similar content.

---

## Dataset

Dataset Used: TMDB 5000 Movies Dataset

Features utilized:

- Title
- Genres
- Keywords
- Overview

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Jupyter Notebook

---

## Project Structure

```bash
Syntecxhub_Movie_Recommendation_System/
│
├── tmdb_5000_movies.csv
├── Movie_Recommendation_System.ipynb
├── movie_recommender.pkl
└── README.md
```

---

## Project Workflow

### 1. Data Loading

Loaded movie metadata from the TMDB dataset.

### 2. Data Cleaning

- Selected relevant columns
- Handled missing values
- Prepared metadata for analysis

### 3. Feature Engineering

Combined movie genres, keywords, and overview into a single text feature.

### 4. Text Vectorization

Converted text into numerical vectors using CountVectorizer.

### 5. Similarity Calculation

Computed cosine similarity between movie vectors.

### 6. Recommendation Generation

Generated recommendations based on similarity scores.

### 7. Model Saving

Saved processed recommendation data using Pickle.

---

## Recommendation Technique

Content-Based Filtering

The recommendation engine suggests movies with similar content by comparing metadata and textual descriptions.

---

## Sample Recommendations

### Input Movie

Avatar

### Recommended Movies

- Guardians of the Galaxy
- Star Trek Into Darkness
- Battle: Los Angeles
- Titan A.E.
- Aliens vs Predator: Requiem

---

## Visualizations Included

- Top Rated Movies Bar Chart
- Dataset Exploration Charts

---

## Output File

### movie_recommender.pkl

Contains processed recommendation data for future use.

---

## How to Run

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Open Notebook

```bash
jupyter notebook
```

Run:

```bash
Movie_Recommendation_System.ipynb
```

---

## Learning Outcomes

- Recommendation Systems
- Content-Based Filtering
- Natural Language Processing
- Text Vectorization
- Cosine Similarity
- Data Preprocessing

---

## Future Improvements

- Collaborative Filtering
- Hybrid Recommendation Systems
- Real-Time Recommendations
- Web Application Deployment
- TMDB API Integration

---

## Conclusion

This project demonstrates how content-based recommendation systems can be built using movie metadata and NLP techniques. By analyzing movie descriptions and attributes, the system generates personalized recommendations for users based on movie similarity.

---

## Author

Dikshitha Reddy Vanga
