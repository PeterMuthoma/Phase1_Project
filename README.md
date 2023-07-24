# Phase 1 Project

Author: [Peter Muthoma](https://github.com/PeterMuthoma/)

## Project Overview

This repository contains a comprehensive analysis of movie performance, exploring the critical relationship between various factors influencing success in the film industry. 

By leveraging a rich dataset encompassing movie titles, ratings, genres, and gross revenue, this project aims to provide valuable and actionable insights for Microsoft's new movie studio leadership. I will use exploratory data analysis to generate insights for these business stakeholder based on these data


### Business Problem

Microsoft, a technology giant, aims to venture into the film industry by establishing a new movie studio. However, lacking expertise in movie production, Microsoft seeks to understand the current landscape of successful films at the box office. The goal of this analysis is to explore and identify the types of films that are currently thriving in the industry.

The analysis will focus on key factors influencing movie success, including genres, average ratings, and gross revenue. By examining the performance of different genres, evaluating critical and audience acclaim, and understanding financial success, we aim to provide actionable insights to the head of Microsoft's new movie studio. These insights will aid in making informed decisions about the type of films to create, ensuring a promising start for Microsoft's venture into original video content.

### The Data

All data for this project are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

The dataset used for this analysis combines information from the above sources, including movie titles, ratings, and financial data. The dataset includes the following columns:
- `tconst`: Unique identifier for each movie title.
- `primary_title`: The primary title of the movie.
- `start_year`: The year the movie was released.
- `runtime_minutes`: The duration of the movie in minutes.
- `genres`: Genres associated with the movie.
- `averagerating`: The average rating of the movie.
- `numvotes`: The number of votes received by the movie.
- `studio`: The production studio responsible for the movie.
- `domestic_gross`: Gross revenue from the domestic market in USD.
- `foreign_gross`: Gross revenue from the foreign market in USD.
- `year`: The year of release of the movie.


### Analysis Overview:

1. **Top Studios Based on Gross Revenue:**

[Alt top genre](zippedData/most popular genre.png)

We identified the top studios based on both foreign and domestic gross revenue. Understanding the performance of leading studios can provide valuable benchmarks for other production houses and help identify potential partnerships for co-productions.

3. **Most Produced Genre:** By analyzing the genre distribution in the dataset, we determined the most produced genre in the film industry. This insight can guide filmmakers and studios in choosing genres that have high demand and widespread audience appeal.

4. **Movie Performance Over the Years:** We tracked the changes in average ratings and the number of votes over the years. This analysis revealed trends in audience engagement and critical acclaim, providing studios with insights into the impact of time on movie success.

5. **Relationship Between Duration and Average Rating:** We investigated the relationship between the duration of a movie and its average rating. This analysis allows filmmakers to understand how the length of a movie influences audience perception and critical reception.

6. **Correlation Between Gross Revenue and Average Rating:** By calculating the correlation between gross revenue and average ratings, we gained insights into how ratings impact movie revenue. This information is vital for studios seeking to strike a balance between financial success and critical acclaim.

7. **Highest Grossing Genres:** We identified the highest grossing genres based on their financial performance. This information can assist studios in tailoring investment strategies and allocating resources effectively to genres with a proven track record of financial success.

## Business Recommendations:

Based on the analysis, we provide the following concrete business recommendations:
1. **Genre-Specific Investment Strategies:** Tailor investment strategies based on genres that consistently perform well financially.
2. **Targeted Marketing and Distribution:** Optimize marketing and distribution strategies based on trends in average ratings and number of votes over time.
3. **Focus on Critical Acclaim and Audience Engagement:** Balance quality content that receives positive reviews from critics with broad audience appeal.


## Folder Structure:


- `data/`: Contains the original data files used in the analysis.
- `notebooks/`: Includes Jupyter notebooks with the data analysis and visualizations.
- `visualizations/`: Stores the charts and visual representations of the findings.
- `README.md`: This file, providing an overview of the project, its objectives, and recommendations.

