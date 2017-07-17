# Exploratory-Data-Analysis
Unit 2 : Working with Data | Lesson 3 : Exploratory Data Analysis 


**Notebook:** [Pandas for Exploratory Data Analysis.ipynb](./Pandas for Exploratory Data Analysis.ipynb)
**Solution:** [Pandas for Exploratory Data Analysis-Solution.ipynb](./solution-code/Pandas for Exploratory Data Analysis-Solution.ipynb)

### Datasets Used (_tsv_: tab-separated, _tbl_: tabular, "|"-separated):
- [drinks.csv](data/drinks.csv): country/continent/servings of beer&wine&spirits&alcohol
- [ufo.csv](data/ufo.csv): ufo sightings, city/state/colors/shape/time

The following datasets go together. The movie IDs and user IDs are consistent between them:
- [movies.tbl](data/movies.tbl): movie titles&info from IMDB
- [user.tbl](data/user.tbl): user ID/age/gender/occupation/zipcode
- [movie_ratings.tsv](data/movie_ratings.tsv): user ID/movie ID/rating/timestamp


### Learning Objectives

- **Understand** what Pandas is
- **Manipulate** Pandas DataFrames and Series
- **Filter and sort** Pandas data
- **Manipulate** DataFrame columns
- **Know** how to handle null and missing values
- **Practice** the split-apply-combine pattern


### Lesson Guide

- [What is Pandas](#pandas)
- [Reading Files, Selecting Columns, and Summarizing](#reading-files)
    - [EXERCISE ONE](#exercise-one)
    
    
- [Filtering and Sorting](#filtering-and-sorting)
    - [EXERCISE TWO](#exercise-two)
    
    
- [Renaming, Adding, and Removing Columns](#columns)
- [Handling Missing Values](#missing-values)
    - [EXERCISE THREE](#exercise-three)
    
    
- [Split-Apply-Combine](#split-apply-combine)
    - [EXERCISE FOUR](#exercise-four)
    
    
- [Selecting Multiple Columns and Filtering Rows](#multiple-columns)
- [Joining (Merging) DataFrames](#joining-dataframes)
- [Other Commonly Used Features](#other-features)
- [Other Less Used Features of Pandas](#uncommon-features)