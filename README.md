# Restaurant Data Analysis Project

## Overview

This project involves data analysis on a restaurant dataset using Python, particularly leveraging the pandas library for data manipulation and Matplotlib for data visualization. The dataset includes information about various aspects of restaurants, such as cuisines, ratings, and customer preferences.

## Contents

- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualizations](#visualizations)
- [Data Transformation](#data-transformation)
- [Advanced Analysis Questions](#advanced-analysis-questions)
- [Project Structure](#project-structure)

## Data Cleaning

- Addressed missing values.
- Standardized data types.
- Cleaned and formatted 'rate' and 'approx_cost' columns.
- Addressed hex characters and unwanted text in columns.

## Exploratory Data Analysis

- Explored unique values in 'cuisines', 'rest_type', 'dish_liked', and other columns.
- Counted occurrences of each value in 'rest_type' and 'dish_liked'.
- Analyzed online orders, booking trends, ratings, and votes.

## Visualizations

- Plotted a count plot for 'rest_type'.
- Created a pie chart for 'listed_in(type)'.
- Visualized the distribution of ratings and votes.
- Plotted horizontal bar chart for the top 10 most liked dishes.

## Data Transformation

- Split 'cuisines' column into lists.
- Extracted unique cuisines.
- Combined counts for duplicate cuisines.
- Flattened lists in 'dish_liked' and visualized top dishes.

## Advanced Analysis Questions

- Analyzed online presence, booking trends, and location-based trends.
- Investigated the relationship between cuisine types and average cost.

## Project Structure

```plaintext
- data/
  - restaurant_data.csv
- notebooks/
  - data_analysis.ipynb
- README.md
