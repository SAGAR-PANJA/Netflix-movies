# Netflix-movies
🔍 Overview
This Power BI dashboard project provides a comprehensive analysis of Netflix's global content library. It visually breaks down the types, distribution, and trends of shows and movies available on the platform. The aim of the project is to gain insights into content availability, genre distribution, rating patterns, and global reach using real-world data.

📥 Data Collection
The dataset was sourced from Kaggle: Netflix Movies and TV Shows.

It includes metadata of Netflix titles such as type, title, director, cast, country, date added, release year, rating, duration, and more.

🧹 Data Cleaning & Preparation
Performed in Power Query Editor within Power BI.

Key transformations:

Removed null values and duplicates.

Split and standardized columns like duration, date_added.

Extracted year from release and added date fields.

Cleaned inconsistent values in country and rating columns.

Formatted data types and renamed columns for clarity.

📐 Data Modeling
Built a star schema with the cleaned dataset.

Created calculated columns and DAX measures to compute:

Total shows

Count of movies vs. TV shows

Year-wise trend of content

Rating-based categorization

Country-wise distribution

📈 Dashboard Features & Visuals
The dashboard includes:

KPI Cards: Total number of shows, movies, and TV shows.

Pie Charts: Show type distribution (Movies vs TV Shows).

Line Graph: Number of shows released over the years.

Bar Chart: Number of shows by content rating (e.g., TV-MA, PG-13).

Donut Chart: Distribution by directors.

Map Visualization: Type of content (movie/TV show) by country.

Slicers: Dynamic filters for show type, release year, and country.

💡 Key Insights
Movies dominate the Netflix catalog, making up over 70% of the total titles.

Most shows were released post-2015, with a significant content boom around 2018–2020.

TV-MA and TV-14 are the most common content ratings.

The United States leads in Netflix content production, followed by India and the UK.

There’s a diverse global spread, but certain regions have a higher proportion of either movies or TV shows.

(https://github.com/SAGAR-PANJA/Netflix-movies/blob/main/Screenshot%202025-05-09%20143408.png)
