# Movie Industry Analysis: Trends in Genres and Actors (1980–2020s)

## Project Overview

This project explores movie industry trends from the 1980s through the 2020s using Python and Pandas.

The analysis focuses on movie genre distribution, changes in genre representation over time, actor appearances, and relationships between actors and movie genres.

The goal is to demonstrate practical data analysis skills through data cleaning, exploratory data analysis (EDA), visualization, and interpretation of results.

## Dataset

**Source:** [Wikipedia Movie Data](https://github.com/prust/wikipedia-movie-data)

The dataset contains **11,215 movie records** after removing one exact duplicate.

The analysis uses four main columns:

- `title` — Movie title
- `year` — Release year
- `cast` — List of actors
- `genres` — List of movie genres

Movie records are loaded directly from the source repository's JSON files.

## Tools and Technologies

- **Python** — Data processing and analysis
- **Pandas** — Data cleaning, transformation, and aggregation
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Interactive analysis and documentation

## Analysis

The project consists of five analytical sections:

1. **Genre Distribution:** Identifying the ten most frequently represented movie genres.
2. **Genre Trends Over Time:** Comparing annual movie counts for Comedy, Drama, and Action.
3. **Top Actors:** Identifying the ten actors with the highest number of movie appearances.
4. **Actor Trends Over Time:** Exploring annual appearance counts for the three most frequently represented actors.
5. **Actor–Genre Analysis:** Comparing the share of movies belonging to the three most common genres across the ten selected actors.

## Key Findings

### Genre Distribution

- Comedy (3,995 movies) and Drama (3,800 movies) were the most frequently represented genres.
- Action ranked third with 1,537 movies.

### Genre Trends

- Drama reached its highest annual count in 1996 (164 movies).
- Comedy peaked in 2009 (133 movies).
- Action peaked in 2013 (60 movies).

### Actor Representation

- Bruce Willis appeared in 104 movie records.
- Samuel L. Jackson appeared in 95 movie records.
- Robert De Niro appeared in 78 movie records.

### Actor–Genre Relationships

- Bruce Willis had the highest share of movies belonging to at least one of the three most common genres (84.6%).
- John Goodman (83.6%) and Robert De Niro (80.8%) also had shares above 80%.
- Willem Dafoe had the lowest share among the ten selected actors (56.5%).

## How to Run

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib notebook
   ```

4. Open `movie_industry_analysis.ipynb` in Jupyter Notebook.
5. Run all cells sequentially.

An internet connection is required to load the JSON datasets from the source repository.

## Limitations

The dataset does not represent the entire global film industry. Movies may belong to multiple genres, and results depend on the completeness and classification of the source records.

The findings describe patterns within the analyzed dataset and should not be interpreted as definitive industry-wide trends.

## Skills Demonstrated

Data cleaning, exploratory data analysis, data transformation, grouping and aggregation, time-series analysis, data visualization, and analytical interpretation.
