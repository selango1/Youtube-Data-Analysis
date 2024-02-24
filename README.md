# Youtube-Data-Analysis
Using Kaggle Dataset to analyze YouTube trends from this [Page](https://www.kaggle.com/datasets/datasnaek/youtube-new?select=CAvideos.csv).
This project analyzes YouTube trending videos data to identify trends based on the time of upload. It includes exploratory data analysis, preprocessing, and time series analysis to understand the factors influencing video trends.

## Overview

YouTube is one of the largest platforms for sharing video content, and understanding the factors that contribute to a video's popularity can provide valuable insights for content creators, marketers, and platform developers. This project aims to analyze YouTube trending videos data to uncover trends based on the time of upload, including hourly and daily patterns.

## Dataset

The dataset used in this project contains information about trending videos on YouTube in various countries, including Canada. It includes features such as video title, channel title, category, publish time, tags, views, likes, dislikes, and comment count. This project aims to analyze YouTube trending videos data to uncover trends based on the time of upload, including hourly and daily patterns.

##Steps
- Time Series Analysis

1. Loading the Dataset: The project starts by loading the YouTube dataset, selecting the data for a specific country (e.g., Canada), and performing basic exploratory data analysis.
2. Mapping Categories: The dataset includes category IDs, which are mapped to category names using a JSON file containing category information.
3. Fixing Data Types: Data types are adjusted for relevant columns, including converting timestamps to datetime format and boolean values to categorical variables.
4. Time Series Analysis:
     Hourly Trends: The project analyzes trends based on the hour of upload, plotting metrics such as views, likes, dislikes, and comment count over the 24-hour period.
     Daily Trends: Trends based on the day of the week are analyzed, plotting metrics by weekday to identify patterns in video uploads.
   
- YouTube trends (Category vs Likes-Dislikes ratio)
1. Loading and Exploring the Dataset: The project starts by loading the dataset and performing exploratory data analysis (EDA) to understand its structure and characteristics. This includes checking basic information, summary statistics, missing values, and the distribution of categories.
2. Mapping Categories: The category IDs in the dataset are mapped to their respective names using a JSON file containing category information. This step enhances the interpretability of the data.
3. Fixing Data Types: Data types are adjusted as needed, including converting timestamps to datetime format and boolean values to categorical variables. This ensures consistency and facilitates further analysis.
4. Visualizing the Data: Various visualizations are created to gain insights into the relationships between different variables. This includes plotting correlation matrices, scatter plots to analyze engagement metrics, and bar plots to compare likes-to-dislikes ratios across different categories.

## Dependencies

-pandas
-numpy
-matplotlib
-json
-dateutil

