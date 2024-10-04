---

# Netflix Data Analysis

## Overview
This project analyzes Netflix data to extract meaningful insights regarding the platform's content, such as TV shows and movies. The dataset contains various features including title, director, cast, country, release date, rating, and more, allowing us to perform extensive exploratory data analysis (EDA) and draw insights about Netflix's content library.

## Dataset
The dataset used in this project consists of the following key features:
- **Show_Id**: Unique ID for each show.
- **Category**: Type of content (Movie or TV Show).
- **Title**: Name of the show.
- **Director**: Director of the content (if applicable).
- **Cast**: Main actors in the content.
- **Country**: Country where the content was produced.
- **Release_Date**: Date when the content was released on Netflix.
- **Rating**: Age rating of the content (e.g., TV-MA, PG-13).
- **Duration**: Duration of the content (minutes for movies, seasons for TV shows).
- **Type**: Genre of the content (e.g., Dramas, Horror Movies).
- **Description**: A brief description of the content.

## Project Objectives
The main objectives of this project are:
1. To explore and clean the Netflix dataset.
2. To analyze the distribution of content in terms of categories (Movies vs TV Shows).
3. To explore trends based on the release year and duration of content.
4. To identify popular genres, countries producing the most content, and content with the highest ratings.
5. To visualize key insights using data visualization libraries such as Matplotlib and Seaborn.

## Tools and Libraries Used
- **Python**: Main programming language used for data analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For plotting and data visualization.
- **Seaborn**: For enhanced data visualization.
- **Jupyter Notebook**: For organizing code and analysis.

## Key Insights
- The majority of Netflix content consists of movies rather than TV shows.
- The USA produces the most content on Netflix, followed by India and the UK.
- Drama and International TV Shows are the most prevalent genres.
- The distribution of content release years shows a significant increase in the number of TV shows and movies added to Netflix from 2015 onwards.
- Most movies have a duration of 80-100 minutes, while TV shows generally run for multiple seasons.

## Visualizations
Several key visualizations are presented in this analysis:
1. Distribution of content by category (Movies vs TV Shows).
2. Count of content by country.
3. Trends in content release over the years.
4. Analysis of the most popular genres on Netflix.
5. Duration distribution for both movies and TV shows.

## Project Live Link
You can view the project and run the code live on Google Colab:
[Netflix Data Analysis - Google Colab](https://colab.research.google.com/drive/1EmnJzpn4lvN11bxs0sX6Dm4iDplA-3a1?usp=sharing)

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Netflix-Data-Analysis.git
   ```
2. Navigate to the project directory and install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook Netflix_Data_Analysis.ipynb
   ```

## Conclusion
This project offers insights into Netflix’s vast content library by analyzing key aspects such as content categories, genres, release trends, and countries producing content. The results of this analysis can help content creators and viewers alike to understand Netflix's content distribution better.

---
