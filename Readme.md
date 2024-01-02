# Movie Data Analysis

## Overview

This project explores a dataset of movies to uncover trends, patterns, and insights related to movie genres, release years, runtimes, popularity, and revenue. It involves data cleaning, feature engineering, exploratory data analysis, and drawing conclusions.

## Dataset

- Source: [https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv)
- Contains information on 5000+ movies, including genres, release dates, budgets, revenue, ratings, and more.

## Key Steps

1. **Data Exploration:**
   - Examine the dataset's structure and summary statistics.
   - Identify missing values and outliers.
2. **Data Cleaning:**
   - Handle missing values by removing rows with missing data.
   - Address outliers using z-score calculations.
3. **Feature Engineering:**
   - Create new features:
     - Release year from release date
     - Runtime categories (short, medium, long)
     - Genre one-hot encoding
     - Revenue-to-budget ratio
     - Popularity and vote average interaction
4. **Exploratory Data Analysis:**
   - Visualize distributions and relationships among variables using Seaborn and Matplotlib.
   - Examine descriptive statistics.
5. **Conclusions:**
   - Identify popular genres over the years.
   - Analyze runtime distributions and genre relationships.
   - Explore revenue-to-budget ratios.
   - Investigate interactions between popularity and vote averages.
   - Answer specific questions:
     - Most popular genre for each year
     - Movie counts in different runtime categories
     - Movie counts for each genre
     - Most popular genre overall
     - Properties of high-revenue movies

## Repository Contents

- `tmdb-movies.csv`: The original movie dataset.
- `Data_Analytics.ipynb`: Jupyter Notebook containing the analysis code.
- `README.md`: This file (provides project overview).

## Dependencies

- pandas
- scipy.stats
- seaborn
- matplotlib

## Instructions for Running the Analysis

1. Download the dataset from the provided link.
2. Install the required dependencies using `pip install`.
3. Run on either Visual Studio Code or Anaconda Jupyter notebook.

## Author

Ruth Abiti Getaneh
