# Movies Dataset Analysis

This project explores a movie dataset to uncover patterns and relationships between various factors, such as budget, runtime, popularity, revenue, and genre. The analysis aims to answer specific questions that offer insights into what makes movies popular, profitable, and widely acclaimed.

## Dataset
The dataset includes information about movies such as:

Budget, revenue, popularity, and runtime
Cast, director, production company, and genre
Release date, vote count, and average rating
Adjusted budget and revenue to account for inflation

## Dataset Summary
Rows: 10,866
Columns: 21

## Data Cleaning: Removed unused columns, handled missing values, and replaced zero values in critical fields like budget.
Questions Addressed in the Analysis
### Does a higher budget lead to greater popularity?
Investigates the relationship between a movie’s budget and its popularity score to understand if a significant investment correlates with a higher public interest.

### Does runtime affect vote count and popularity?
Examines whether movies of different lengths attract more votes or are more popular on average.

### Does higher popularity lead to higher profits?
Explores whether movies that score higher on popularity also tend to generate higher profits.

### What features are associated with the top 10 revenue-generating movies?
Analyzes attributes like runtime, vote count, and average rating to identify common traits among the most profitable movies.

### Which genres are most popular from year to year?
Looks at genre trends over time to determine which types of movies have been most popular historically.

## Methodology
Data Cleaning: Removed unnecessary columns and filled missing values in crucial fields.
Visualization: Used matplotlib and seaborn for visual exploration and comparison of trends in budget, popularity, runtime, profit, and genre frequency.
Statistical Analysis: Performed grouping and calculation of average values for different movie characteristics to answer each question.

## Key Findings
Budget and Popularity:
Higher-budget movies are associated with significantly higher popularity, showing an approximate 50% increase in popularity compared to lower-budget films.

Runtime and Popularity:
Movies shorter than 200 minutes tend to be more popular, while movies longer than 200 minutes generally struggle to achieve high popularity.

Popularity and Profits:
Movies with higher popularity scores tend to yield substantially higher profits on average.

Top Revenue Movies’ Traits:
The top revenue movies tend to have runtimes between 120–200 minutes and high vote counts, suggesting these factors may contribute to financial success.

Genre Popularity Over Time:
The most popular genres historically are Drama, Comedy, Action, Horror, and Adventure, with the number of movies released per year increasing over time.

## Limitations
Data Quality: Missing values and zeros in important columns like budget and revenue may affect accuracy.
Popularity Measurement: Limited understanding of how popularity and vote count are determined.
Currency & Inflation: Budget and revenue are presented in various currencies without conversion, and inflation may not be fully accounted for.

## Requirements
To run this notebook, install the following libraries:

pip install pandas matplotlib seaborn numpy
