# SQL Analysis Case Study - IMDB Dataset

This repository contains the SQL analysis case study focused on the IMDB dataset. The goal of this project is to perform an in-depth analysis of the IMDB dataset using SQL queries to extract insights related to movie ratings, genres, actors, and more.

## Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [SQL Queries](#sql-queries)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview

In this case study, we analyze the IMDB dataset to uncover trends, patterns, and correlations related to movies, ratings, and other metadata. The project leverages SQL queries to perform the following:

- Extract movie information, ratings, and metadata.
- Analyze trends by genres, years, and actors.
- Investigate relationships between variables like rating and genre or box office performance.
- Generate aggregate reports for movie statistics.

## Objectives

The primary objectives of this case study are to:

- Perform exploratory data analysis (EDA) on the IMDB dataset using SQL.
- Execute complex SQL queries to gather insights on ratings, movie popularity, and trends.
- Visualize the results for easy interpretation and reporting.

## Dataset

The dataset used in this analysis contains data from IMDB, including:
- Movie titles and IDs
- Ratings and reviews
- Genres, cast, crew, and other movie-related metadata
- Year of release, box office data, etc.

You can download the dataset from [IMDB Dataset](https://www.imdb.com/interfaces/).

## Technologies Used

- **SQL**: For querying and analyzing the IMDB dataset.
- **SQLite/MySQL/PostgreSQL**: Database management system for running SQL queries.
- **Jupyter Notebook** (optional): For documenting and visualizing analysis steps (if applicable).
- **Python (optional)**: For data visualization and advanced analysis (e.g., using libraries like `matplotlib` and `seaborn`).

## SQL Queries

This project contains the following SQL queries:
1. **Query 1**: Find the top-rated movies by genre.
2. **Query 2**: Analyze the average movie rating per year.
3. **Query 3**: Identify the most popular actors and their associated movies.
4. **Query 4**: Compare the average ratings for movies based on their release decade.
5. **Query 5**: Get movies with the highest box office earnings and their ratings.

The SQL queries are organized in separate `.sql` files, one for each query.

## Setup

To run this analysis locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/sql-analysis-imdb.git
