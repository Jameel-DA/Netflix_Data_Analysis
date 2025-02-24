# Netflix Movies and TV Shows Analysis

## Description
This project analyzes a dataset of Netflix movies and TV shows to uncover insights into genres, popularity trends, voting patterns, and release year distributions. The goal is to identify the most frequent genres, understand vote distributions, and determine which years had the highest movie production.

## Tools & Technologies
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Environment**: Jupyter Notebook

## Dataset
- **Source**: `mymoviedb.csv` (includes columns like `Genre`, `Vote_Count`, `Vote_Average`, `Release_Date`, and `Popularity`).
- **Cleaned Data**: After preprocessing, the dataset contains **7 columns** and **9,826 rows**.

## Key Steps
1. **Data Cleaning**:
   - Removed missing values and duplicates.
   - Converted `Release_Date` to datetime and extracted the year.
   - Dropped irrelevant columns (`Overview`, `Original_Language`, `Poster_Url`).
2. **Feature Engineering**:
   - Categorized `Vote_Average` into labels: "Not Popular", "Below Avg", "Average", "Popular".
   - Split and exploded the `Genre` column for granular analysis.
3. **Visualization**:
   - Analyzed genre frequency, vote distribution, and release year trends.

## Key Findings
- 🎭 **Most Frequent Genre**: Drama (over 14% of entries).
- 🏆 **Highest Popularity Movie**: *Spider-Man: No Way Home* (Genres: Action, Adventure, Science Fiction).
- 📉 **Lowest Popularity Movie**: *The United States, Thread* (Genres: Music, Drama, War, Sci-Fi, History).
- 📅 **Peak Release Year**: 2020 had the most movies.
- 🗳️ **Vote Distribution**: 25.5% of movies fell into the "Popular" category.
