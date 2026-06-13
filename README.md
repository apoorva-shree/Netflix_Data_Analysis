# Netflix Movies Data Analysis
# Project Overview

This project explores a Netflix Movies dataset to uncover trends in movie genres, popularity, ratings, and release patterns using Python-based data analysis and visualization techniques.

The goal of this project is to perform Exploratory Data Analysis (EDA), clean and preprocess raw movie data, and generate meaningful insights that help understand audience preferences and movie characteristics.

# Objectives
-Clean and preprocess movie dataset

-Analyze genre distribution across movies

-Examine movie popularity trends

-Study rating patterns using vote averages

-Identify the most and least popular movies

-Explore movie release trends over the years

-Visualize relationships between numerical features

# Technologies Used
-Python

-Pandas

-NumPy

-Matplotlib

-Seaborn

-Jupyter Notebook

# Dataset Features

The dataset contains information such as:

-Movie Title

-Genre

-Release Date

-Popularity Score

-Vote Average

-Vote Count

-Overview

# Data Preprocessing

Several preprocessing steps were performed before analysis:

1.Date Formatting

-Converted Release_Date column to datetime format.

-Extracted only the release year for easier trend analysis.

2.Feature Selection

Removed unnecessary columns:

-Overview

-Poster_URL

-Original_Language

3.Rating Categorization

The Vote_Average column was categorized into:

-Popular

-Average

-Below Average

-Not Popular

4.Missing Values Handling

Removed rows containing null values.

5.Genre Transformation

-Split movies containing multiple genres.

-Used Pandas explode() to analyze each genre individually.

# Exploratory Data Analysis
# Genre Distribution

Analyzed the frequency of movie genres available in the dataset.

# Key Finding:
Drama emerged as the most common genre.

# Vote Average Analysis

Visualized the distribution of movie ratings after categorization.

# Key Finding:
Most movies fall into the Average rating category.

# Popularity Analysis

Identified:

-Most Popular Movie
-Least Popular Movie

# Most Popular Movie:
🎥 Spider-Man: No Way Home

# Release Year Trends

Studied how movie releases are distributed across years.

Insights were obtained using histogram-based visualization.

# Correlation Analysis

Generated a correlation heatmap to understand relationships among numerical variables such as:

-Popularity

-Vote Count

-Vote Average

-Top 10 Most Popular Movies

Created a ranking of the top-performing movies based on popularity scores and visualized the results using bar charts.

# Visualizations Included

✔ Genre Distribution Count Plot

✔ Vote Average Distribution Plot

✔ Release Year Histogram

✔ Correlation Heatmap

✔ Top 10 Popular Movies Bar Chart

# Key Insights

Drama is the most dominant genre.

Most movies belong to the Average rating category.

Spider-Man: No Way Home has the highest popularity score.

Movie releases show strong growth in recent years.

Popularity and vote-related features exhibit meaningful correlations
