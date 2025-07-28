# 🎬 Netflix Movie Data Analysis

This project explores a dataset of Netflix movies and TV shows using Python. Through exploratory data analysis (EDA), we uncover trends in content release, popularity, genres, and viewer engagement. The goal is to understand what makes Netflix content successful and how it's evolved over time.

---

## 📌 Objectives

- Clean and preprocess raw Netflix data
- Analyze content trends by year, genre, and popularity
- Visualize key insights using Python (Matplotlib & Seaborn)
- Prepare the data for potential machine learning or dashboarding

---

## 📊 Dataset Overview

The dataset includes:
- 🎞️ Title
- 📆 Release Date
- ⭐ Popularity Scores
- 📈 Vote Counts & Averages
- 🧬 Genre Information

> 📁 Note: Genre column was processed using string manipulation and exploded to analyze multi-genre content individually.

---

## 🧰 Tools & Technologies

| Tool           | Purpose                            |
|----------------|------------------------------------|
| Python         | Programming Language               |
| Pandas         | Data Cleaning & Manipulation       |
| NumPy          | Numerical Operations               |
| Matplotlib     | Data Visualization                 |
| Seaborn        | Statistical Visualization          |
| Jupyter Notebook | Exploratory Coding Environment  |

---

## 📈 Exploratory Data Analysis Highlights

- 📅 Most active years for Netflix content: `2020`, `2021`, `2022`
- 🌍 Top genres: `Action`, `Drama`, `Comedy`, `Thriller`
- 📊 Distribution of vote averages indicates content clusters around "popular" or "below average"
- 🔍 Multiple genres per title handled using `.explode()` to analyze granular patterns
- 🎯 Popular titles tend to have higher vote counts and ratings

---

## 🔥 Key Visuals

| Visual                          | Description                                  |
|----------------------------------|----------------------------------------------|
| 📉 Content Released Over Years  | Trend of Netflix content additions           |
| 🎭 Genre Distribution           | Count of movies per genre                    |
| ⭐ Popular vs Vote Average      | How user ratings relate to popularity        |


---

## 🧹 Data Preprocessing

- Removed irrelevant columns: `Overview`, `Poster_Url`, etc.
- Converted `Release_Date` to datetime
- Handled nulls and missing genre info
- Split multi-genre entries and exploded into multiple rows
- Categorical casting for optimized performance

---
## 🤝 Acknowledgments 
This project was inspired by hands-on learning from:

- 📺 [The Data Girl YouTube Tutorial](https://www.youtube.com/watch?v=tjIWRqqMDaw&t=3693s)  
- 📊 [Kaggle and other open-source datasets](https://www.kaggle.com/)

---

**I'd love to connect **

- 🔗 [LinkedIn](https://www.linkedin.com/in/sreejitaguha-dataanalyst/)  
- 📫 sreejita.guha@yahoo.com  
- 💻 [GitHub](https://github.com/SREEJITA1904)


