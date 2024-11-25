# 1990s Netflix Movie Insights

This project performs exploratory data analysis (EDA) on Netflix movie data to gain insights into movies released during the 1990s.

## Project Description

The goal of this project is to analyze Netflix's movie dataset focusing on the 1990s decade (1990-1999). The analysis addresses the following questions:

1. **What was the most frequent movie duration in the 1990s?**
2. **How many short action movies (less than 90 minutes) were released in the 1990s?**

## Dataset

The dataset used is `netflix_data.csv`, which contains information about Netflix titles including movies and TV shows, their release year, duration, and genre.

## Requirements

- Python 3.x
- pandas
- matplotlib

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/josedanielchg/1990s-netflix-movie-insight.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd 1990s-netflix-movie-insight
   ```

3. **Install the required packages**:

   ```bash
   pip install pandas matplotlib
   ```

## Code Explanation

- **Import Libraries**: Import `pandas` for data manipulation and `matplotlib.pyplot` for data visualization.
- **Read Data**: Load the dataset `netflix_data.csv` into a DataFrame.
- **Data Filtering**:
  - Filter the data to include only movies.
  - Further filter movies released between 1990 and 1999.
- **Data Visualization**:
  - Plot a histogram of movie durations to find the most frequent duration.
- **Calculate Duration**:
  - Identify the approximate most frequent movie duration and store it in the variable `duration`.
- **Short Action Movies Count**:
  - Filter the data to include only action movies.
  - Use a loop to count how many action movies have a duration less than 90 minutes.
  - Store the count in the variable `short_movie_count`.

## Results

- **Most Frequent Movie Duration**: The most common movie duration in the 1990s is approximately **100 minutes**.
- **Number of Short Action Movies**: There are **7** short action movies (less than 90 minutes) released in the 1990s.