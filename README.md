# 🎬 TMDB Movie Data Analysis

An Exploratory Data Analysis (EDA) project on the TMDB Movie Dataset using Python. This project focuses on cleaning, transforming, and visualizing movie data to uncover meaningful insights about genres, popularity, votes, and release trends.

---

## 📌 Project Overview

This project demonstrates the complete data analysis workflow:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Insight Generation

The goal is to analyze movie trends and answer real-world business questions using Python.

---

## 🎯 Objectives

- Clean and preprocess movie data.
- Explore genre distribution.
- Analyze movie popularity and ratings.
- Identify release trends over the years.
- Generate insights through visualization.

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset

The project uses the **TMDB Movie Dataset**, which contains information such as:

- Movie Title
- Genre
- Popularity
- Vote Average
- Vote Count
- Release Date
- Runtime
- Original Language
- Overview
- Poster URL

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns:
  - Overview
  - Original Language
  - Poster URL
- Checked and handled missing values.
- Converted the Release Date column into datetime format.
- Cleaned and standardized the Genre column.
- Categorized movies based on Vote Average into:
  - Popular
  - Average
  - Below Average
  - Not Popular

---

## 📊 Exploratory Data Analysis

The project answers the following questions:

### 1. Which genre appears most frequently?

Identified the most common movie genre in the dataset.

### 2. Which genre has the highest number of votes?

Analyzed audience voting trends across genres.

### 3. Which movie has the highest popularity?

Found the most popular movie and identified its genres.

### 4. Which movie has the lowest popularity?

Determined the least popular movie in the dataset.

### 5. Which year had the highest number of movie releases?

Analyzed yearly release trends using visualizations.

---

## 📈 Visualizations

The project includes multiple visualizations using Matplotlib and Seaborn, such as:

- Histogram
- Count Plot
- Bar Chart
- Line Plot
- Genre Distribution
- Release Year Analysis

---

## 🔍 Key Insights

- Drama is the most frequent genre.
- Drama also receives the highest audience votes.
- *Spider-Man: No Way Home* has the highest popularity score.
- The highest number of movies were released in 2020.
- Data preprocessing significantly improved the quality of analysis.

---

## 📁 Project Structure

```
tmdb-movie-data-analysis/
│
├── data/
│   └── movie_dataset.csv
│
├── notebooks/
│   └── TMDB_Movie_Data_Analysis.ipynb
│
├── images/
│   ├── genre_distribution.png
│   ├── popularity_analysis.png
│   ├── release_year.png
│   └── histogram.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/tmdb-movie-data-analysis.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 🚀 Future Improvements

- Interactive dashboard using Plotly
- Streamlit web application
- Movie recommendation system
- Advanced statistical analysis
- Machine Learning-based popularity prediction

---

