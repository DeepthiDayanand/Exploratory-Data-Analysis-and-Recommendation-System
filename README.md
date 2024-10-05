# Exploratory-Data-Analysis

## Overview
This project performs **exploratory data analysis** on the movielens dataset. The system leverages historical rating data, user information, and movie metadata to provide personalized movie recommendations. The project includes an analysis of user and movie data, and it compares different recommendation algorithms to improve the relevance of suggestions.

## Dataset
The [movielens dataset](https://grouplens.org/datasets/movielens/1m/) used in this project consists of three main components:
1. **Ratings Data**: Contains user IDs, movie IDs, and their corresponding ratings.
2. **User Data**: Provides information about the users (e.g., demographics, age, gender).
3. **Movie Data**: Metadata about movies, including titles, genres, and descriptions.

## Project Structure
1. **Libraries**
   - The project utilizes Python libraries such as `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `surprise` for data analysis, visualization, and building recommendation algorithms.

2. **Data Preprocessing**
   - Data from different sources such as movie ratings, user information, and movie details are loaded, cleaned, and preprocessed. This includes handling missing values, formatting, and merging datasets.

3. **Exploratory Data Analysis (EDA)**
   - **Rating Data**: Analyzing the distribution of ratings, average ratings per user, and most frequently rated movies.
   - **User Data**: Investigating user activity levels and patterns.
   - **Movie Data**: Identifying the most popular and highest-rated movies, along with genre distribution.

4. **Collaborative Filtering Techniques**
   - **User-based Collaborative Filtering**: Recommending movies by finding similar users based on their ratings.
   - **Item-based Collaborative Filtering**: Recommending movies based on similarities between items (movies) rated by users.

## Dependencies

The project requires the following libraries:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations and handling large datasets.
- **scikit-learn**: For content-based filtering and machine learning tasks.
- **surprise**: For collaborative filtering and recommendation system implementations.
- **matplotlib**: For data visualization.
- **seaborn**: For advanced statistical visualizations.
