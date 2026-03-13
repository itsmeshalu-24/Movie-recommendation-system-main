# 🎬 Movie Recommendation System

This project is a **Capstone Project** completed as part of the **Edureka Data Science with SQL** course.  
It showcases a complete movie recommendation system using the **MovieLens dataset**.

---

## 📚 About the Project

The project implements three types of recommendation systems:

1️⃣ **Popularity-Based Recommender**:  
Recommends top-rated movies in a selected genre with a minimum review threshold.

2️⃣ **Content-Based Recommender**:  
Suggests movies similar to a selected one based on genre similarity using **TF-IDF** and **Cosine Similarity**.

3️⃣ **Collaborative Filtering Recommender**:  
Provides personalized movie recommendations based on ratings from similar users.

Interactive inputs and colorful visualizations make it easy to experiment with different genres, movies, and user IDs.

---

## 🎯 Objective

The goal of this project is to apply data science techniques to create personalized content discovery systems, similar to platforms like Netflix or Prime Video.

---
## 🛠️ Tools Used

- **Python**: Programming language
- **Jupyter Notebook**: Interactive coding environment
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **scikit-learn**: Machine learning models and similarity computations
- **Plotly**: Interactive data visualizations
- **MovieLens Dataset**: Real-world dataset for movies and ratings
- **SQL** (Course Context): While this project uses CSVs, concepts from **SQL querying and data extraction** are applied as part of the Edureka Data Science with SQL course

---

## 📂 Project Structure

movie-recommendation-system/

├── README.md

├── LICENSE (MIT)

├── movie_recommendation_system.ipynb

├── movies.csv

├── ratings.csv

---

- **README.md**: This documentation file  
- **LICENSE**: Open-source MIT License  
- **movie_recommendation_system.ipynb**: Main Jupyter Notebook with code and explanations  
- **movies.csv**: Movie metadata (ID, title, genres)  
- **ratings.csv**: User ratings data (user ID, movie ID, rating, timestamp)

---

## 📊 Exploratory Data Analysis (EDA)

- 🎭 **Genre Distribution**: Visualized as a colorful horizontal bar chart  
- ⭐ **Rating Distribution**: Visualized as a histogram with interactive features  

These plots are generated using **Plotly** and are fully interactive in the notebook.

---
## 🎯 Recommender Systems Implemented

### 1️⃣ Popularity-Based Recommender
- Input: Genre, Minimum number of reviews, Number of recommendations
- Output: Top-rated movies in the selected genre

### 2️⃣ Content-Based Recommender
- Input: Movie title, Number of similar movies to recommend
- Output: Similar movies based on genre similarity using TF-IDF and Cosine Similarity

### 3️⃣ Collaborative Filtering Recommender
- Input: User ID, Number of similar users (K), Number of recommendations
- Output: Personalized movie recommendations based on user similarity

---
## 🏃‍♂️ Getting Started

1️⃣ Clone this repository:
git clone https://github.com/itsmeshalu-24/Movie-recommendation-system-main

---
## 📚 Dataset Description

The data used in this project comes from the [MovieLens dataset](https://grouplens.org/datasets/movielens/100k/), a widely used dataset in recommender systems research.

- **movies.csv**: Contains `movieId`, `title`, and `genres`.  
- **ratings.csv**: Contains `userId`, `movieId`, `rating`, and `timestamp`.

---



- Key Highlights
  
1. Interactive user inputs for all three recommdation models

2. Clear and colorful data visualizations using Plotly

3. Clean and well-commented code with explanations

4.Real-world application of data science concepts from the **Edureka Data Science with SQL** course

---
- Future Enhancements

Add advanced collaborative filtering (SVD, matrix factorization)

Build a web-based interface using Streamlit or Flask

Incorporate user feedback for dynamic recommendations


---

- License

This project is licensed under the MIT License.
See the LICENSE file for full details.

---
👨‍💻 Author
**Shalu Singh**

Edureka Data Science with SQL Learner

Connect on LinkedIn https://www.linkedin.com/in/shalu-singh-0561162b2/


---

**Course Details**
This couse covers following topics :

- Python Programming

- Probabilty and Statistics

- Supervised Machine Learning

- Unsupervised Machine Learning

- Deep learning

- Natural language processing

- Data visualization using Tableau

- SQL for Data Science

---
✅ Conclusion


This Movie Recommendation System demonstrates how data science can enhance user experience through personalized content discovery. With practical implementations of popularity-based, content-based, and collaborative filtering models, this project bridges the gap between learning and real-world applications.
