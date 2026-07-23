# Netflix Titles — Exploratory Data Analysis

Exploratory data analysis of the Netflix titles catalog, uncovering patterns in content type, genre, country of origin, ratings, and release trends.

## 📊 Overview

This project analyzes Netflix's global content catalog to answer key questions:

- What's the split between Movies and TV Shows?
- Which countries produce the most Netflix content?
- What are the most common genres and content ratings?
- Who are the most frequently featured directors and actors?
- How has Netflix's content library grown over time?
- What's the typical movie runtime?

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `netflix_titles_csv.xlsx` | Dataset — Netflix titles with type, cast, country, genre, rating, duration, and release info |
| `netflix_eda.ipynb` | Analysis notebook: data cleaning and visualizations |

## 🧰 Tech Stack

- Python 3
- pandas — data cleaning and aggregation
- seaborn / matplotlib — visualization

## 🔍 Methodology

1. **Data Cleaning** — filled missing country values with "Unknown", dropped rows missing date added, duration, or rating, converted date fields to datetime
2. **Feature Simplification** — reduced multi-genre `listed_in` field to primary genre per title for cleaner aggregation
3. **Exploratory Data Analysis** — aggregated by content type, country, genre, rating, director, and cast
4. **Visualization** — bar charts, line plots, and a histogram to surface patterns across the catalog

## 📈 Key Findings

- **Content type**: Movies significantly outnumber TV Shows on Netflix (roughly 6,100 vs. 2,650 titles).
- **Top country**: The United States leads by a wide margin, followed by India and the UK.
- **Top genre**: Dramas is the most common genre, followed by Comedies and Action & Adventure.
- **Ratings**: TV-MA is the most common content rating, followed by TV-14.
- **Growth**: Netflix's content library grew sharply from the mid-2010s, peaking around 2018–2019.
- **Movie runtime**: Most movies fall between 80–120 minutes.

## 📁 Dataset

Source: [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/)

## ✍️ Author

Aneesh Fathima

## 📄 License

This project is for educational and portfolio purposes. Dataset sourced from Kaggle under its respective license.
