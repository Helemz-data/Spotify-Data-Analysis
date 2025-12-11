Spotify Data Analysis

Comprehensive Exploratory Data Analysis (EDA) of Spotify tracks, genres, and popularity trends

Overview

This project performs an in-depth analysis of Spotify track data, focusing on genre trends, release patterns, and factors associated with track popularity. Using Pandas, Matplotlib, and exploratory data engineering techniques, the project transforms raw metadata into actionable insights for music analytics, artist profiling, and market behavior understanding.

Objectives

Clean and preprocess Spotify metadata.

Unpack and normalize nested genre information.

Explore genre-level popularity trends across years and months.

Identify the most popular genres globally.

Visualize temporal and seasonal music trends.

Key Features
1. Data Cleaning & Preprocessing

Removal of missing values across critical fields.

Parsing and converting date fields into standard datetime formats.

Normalization of list-like genre strings into proper Python lists.

Dataset transformation using .explode() for genre-wise analysis.

2. Feature Engineering

Extracted year and month from album release dates.

Structured dataset to support trend analysis across genres and time.

3. Trend Analysis

Genre Popularity Over Time (Yearly)

Computed average popularity scores per genre per year.

Highlighted top-performing genres with sufficient data.

Seasonal Genre Performance (Monthly)

Detected cyclic performance patterns across the calendar year.

4. Genre Popularity Ranking

Identified top genres based on average track popularity.

Visualized leading genres using bar charts for quick insight.

Technologies Used
Technology	Purpose
Python	Core programming
Pandas	Data manipulation & cleaning
Matplotlib	Data visualization
Seaborn	Complementary analytics
NumPy	Numerical operations
Google Colab	Development environment

Visualizations Included

Yearly genre popularity trends

Monthly/seasonal performance analysis

Top 20 genres ranked by popularity

Genre distribution and patterns

How to Run the Notebook

Insights Summary

Certain genres consistently outperform others in terms of average popularity.

Genre popularity exhibits both long-term trends and seasonal fluctuations.

Tracks by artists with multiple genre associations allow for richer cross-genre analysis.
