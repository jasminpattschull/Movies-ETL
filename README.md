# Movies-ETL
Module 8

#Wiki, Kaggle and Ratings Movie Analysis

## Overview

This analysis was comprised of four parts.  The first deliverable was to write an ETL (extract, transform and load) function to read three data files.  Those data files were the movies_metadata (csv), ratings (csv) and wikipedia-movies (json) files. The second deliverable was to extract and transform the Wikipedia data. The third deliverable was to extract and transform the Kaggle data. The final deliverable was creating the movie database.

## Results

The files required cleansing via numerous steps. The resulting dataframe was movies_df and two tables called movies and ratings were uploaded to pgAdmin4.

## Summary
The movies table contained 6,052 rows and the ratings table contained 24,289 rows.

![movies_query](https://user-images.githubusercontent.com/90632470/141873509-fa2b477e-511a-4df4-8ed6-5c8c3cfacc98.png)

![ratings_query](https://user-images.githubusercontent.com/90632470/141873529-d32aa8f1-e012-436f-97f0-b2cfb30db171.png)
