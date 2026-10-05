# Netflix Movies Analysis — Tableau

An interactive Tableau project that analyzes a dataset of 16,000 movies to understand patterns in ratings, genres, countries, languages, and audience engagement.

The project uses **Excel for data preparation** and **Tableau for analysis and visualization**.

---

## 📌 Project Overview

The main objective of this project is to explore the movie dataset and answer questions such as:

- Which genres have the most movies?
- Which movies are highly rated?
- How are movies distributed across different countries?
- How are movie ratings distributed?
- How do average ratings change by release year?
- Which genres have higher average ratings?
- Which languages are most represented?
- Which highly rated movies also have strong audience engagement?

---

## 📊 Dataset

- **Total Movies:** 16,000
- **Release Years:** 2010–2025
- **Average Rating:** 6.3
- **Total Votes:** 11.5M
- **Main fields:** Title, Release Year, Rating, Vote Count, Popularity, Genre, Country, Language

The dataset contains movie information along with rating, popularity, audience votes, genre, country, and language details.

---

## 🧹 Data Preparation

The data was prepared using **Excel and Tableau**.

Main preparation steps included:

- Checking for duplicate and missing values
- Cleaning and standardizing rating values
- Creating rating bins for rating distribution analysis
- Separating genre and country information into supporting tables
- Creating language aliases for commonly represented language codes
- Preparing the data for Tableau visualization

---

## 📈 Dashboards

### Dashboard 1 — Netflix Movies: Global Overview

This dashboard provides an overall view of the movie catalog.

It includes: (4 KPIs | 4 Charts)

- **Total Movies**
- **Average Rating**
- **Total Genres**
- **Total Votes**
- Top 10 Genres
- Top Rated Movies
- Global Movie Distribution
- Rating Distribution

### Dashboard 2 — Netflix Movies: Trends & Insights

This dashboard focuses on patterns and comparisons within the dataset.

It includes: (3 Charts)

- Average Rating by Release Year
- Average Rating by Genre
- Top 10 Movie Languages

---

## 🔎 Key Insights

- **Drama** is the largest genre by number of movies.
- **Documentary** has the highest average rating among the genres shown, at approximately **7.1**.
- **United States** has the highest number of movies in the global distribution analysis.
- **English** is the most represented language, with **9,534 movie records**.
- Most movie ratings are concentrated around the **5–7 range**.
- Among the top-rated movies shown, **Interstellar** has the highest vote count with **36,625 votes**.

---

## ⭐ Top Rated Movies Criteria

To make the Top Rated Movies analysis more meaningful, the project uses two conditions:

- **Rating ≥ 7.0**
- **Vote Count ≥ 1,000**

This avoids selecting movies only because they have a high rating with very few votes and provides a better indication of audience engagement.

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data preparation
- **Tableau** — Data analysis and visualization

---

## 🎯 Project Outcome

This project demonstrates how a large movie dataset can be transformed into an interactive Tableau dashboard and used to identify meaningful patterns across **ratings, genres, countries, languages, release years, and audience engagement**.

---

## 👤 Author

**Krishna Thombare**

Built as a data analytics and visualization portfolio project using **Excel and Tableau**.
