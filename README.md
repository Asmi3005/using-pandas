# Movie Data Analysis and Visualization

## Overview  
This project focuses on analyzing a movie dataset to explore relationships between movie attributes, such as IMDb score, movie income, budget, and duration. Using the Pandas library, we perform data cleaning, transformation, and visualization to derive insights from the dataset.

### Learning Objectives  
- Data cleaning and preparation with Pandas.  
- Creating and customizing various visualizations using Pandas plotting functions.  
- Analyzing and answering key business and analytical questions from the data.

## Project Structure  

### 1. Importing and Loading Data  
- Import essential libraries, especially `pandas`.  
- Load the dataset (in JSON format) using `pd.read_json()` and view the first few rows.  
- Check the dataframe's shape and data types of columns.

### 2. Data Preparation  
- Remove unnecessary columns such as `movie_imdb_link`, `num_critic_for_reviews`, and `genres`.  
- Convert data types (e.g., `title_year` column to integer).  
- Rename columns for clarity (`gross` to `movie_income` and `budget` to `movie_budget`).  

### 3. Data Analysis  
- Visualize the distribution of `duration` and `imdb_score` using histograms in Pandas.  
- Find and explore movies with IMDb scores below 4.  
- Analyze movies produced in the USA and their IMDb score distribution.

### 4. Analytical Questions  
- **Question 1**: Identify the years with the highest and lowest number of movies produced.  
    - Group movies by year and plot the results using a line chart in Pandas.  
- **Question 2**: Identify the years with the minimum and maximum average IMDb scores.  
    - Group movies by year and calculate average IMDb scores.  
    - Visualize the result using a bar chart in Pandas.  
- **Question 3**: Identify the years with the minimum and maximum movie budgets.  
    - Sum the movie budgets by year and visualize the results using a line chart in Pandas.  
- **Question 4**: Investigate the relationship between IMDb score and movie income.  
    - Use scatter plots and correlation matrices to analyze the relationship, all within Pandas.

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: pandas  

## Key Outcomes  
- Performed data cleaning, transformation, and visualization.  
- Gained insights into movie trends such as production years, IMDb scores, and budgets.  
- Analyzed the relationship between IMDb score and movie income using Pandas visualization tools.

## Dataset  
The dataset used in this project contains movie-related data such as IMDb scores, movie budgets, income, duration, country of origin, and more. It is loaded in JSON format using Pandas.  

