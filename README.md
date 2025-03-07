# FIFA Player Data Analysis

## Project Overview
This project aims to analyze the FIFA player dataset to understand player statistics, club performance, and wage distribution. The analysis includes data exploration, visualization, and the application of statistical methods to derive insights.

## Dataset
The dataset contains information about FIFA players, including their overall rating, potential, club, nationality, wage, and value. The dataset has been cleaned and preprocessed for analysis.

## Methodology
1. **Data Exploration**: Initial exploration of the dataset to understand its structure and summary statistics.
2. **Data Cleaning**: Conversion of wage and value columns to numeric format using lambda functions.
3. **Groupby Operations**: Aggregation of data to find average overall ratings by club and total wages by nationality.
4. **Visualization**: Creation of histograms, scatter plots, and bar plots to visualize the distribution of overall ratings, the relationship between player value and wage, and the top clubs by average overall rating.

## Results
- The distribution of overall ratings shows a normal distribution with most players rated between 60 and 80.
- There is a positive correlation between player value and wage, indicating that higher-valued players tend to earn more.
- The top clubs by average overall rating include FC Barcelona, Real Madrid, and FC Bayern München.

## Future Work
- Augment the dataset with web-scraped data for additional insights.
- Apply statistical tests like Chi-Square to explore relationships between categorical variables.
- Create a Tableau dashboard for interactive data visualization.

## How to Run the Script
1. Ensure you have Python installed along with the required libraries (pandas, matplotlib, seaborn).
2. Download the dataset and place it in the same directory as the script.
3. Run the script using a Python interpreter.

## Dependencies
- pandas
- matplotlib
- seaborn
- numpy
- kagglehub
- glob 
- re
- statsmodels.api
- scipy.stats as st
