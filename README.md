# 🎬 Netflix Data Analysis

This project analyzes and visualizes data from the **Netflix Titles Dataset** using Python, **Pandas**, and **Matplotlib**.  
It provides insights into the types of content available, distribution of ratings, duration trends, and content production across countries and years.

---

## 📊 Project Overview

The Netflix dataset includes information about movies and TV shows available on the platform, including title, director, cast, country, release year, rating, and duration.  
This project performs:
- Data cleaning and preparation  
- Exploratory data analysis (EDA)  
- Visualization of key insights

---

## 🧰 Tech Stack

- **Python 3**
- **Pandas** — for data manipulation  
- **Matplotlib** — for visualization  

---

## 📂 Dataset

- **File used:** `netflix_titles.csv`  
  You can download it from [Netflix Movies and TV Shows dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🚀 Features & Visualizations

1. **Movies vs TV Shows Count**  
   Bar chart comparing the number of movies and TV shows.  
   📁 Output: `movies_tvshows.png`

2. **Content Rating Distribution**  
   Pie chart showing percentage share of each rating.  
   📁 Output: `ratings.png`

3. **Movies Duration Analysis**  
   Histogram displaying movie durations in minutes.  
   📁 Output: `movies_duration.png`

4. **Release Count Over Years**  
   Scatter plot showing how many titles were released per year.  
   📁 Output: `release_count.png`

5. **Top 10 Countries by Content Count**  
   Horizontal bar chart showing countries producing the most Netflix content.  
   📁 Output: `country_count.png`

6. **Movies vs TV Shows Over Time**  
   Line plots comparing release trends of movies and TV shows by year.  
   📁 Output: `movie_tvshows_comparision.png`

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/SNEH-17PATEL/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Install Dependencies
```bash
pip install pandas matplotlib
```

### 3. Add Dataset
Place the `netflix_titles.csv` file in the project directory.
