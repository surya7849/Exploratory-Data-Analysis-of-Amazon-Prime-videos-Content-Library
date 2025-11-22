# Exploratory-Data-Analysis-of-Amazon-Prime-videos-Content-Library
This project performs Exploratory Data Analysis( EDA ) on the Amazon Prime Video content library to uncover patterns in genres, release years, ratings, and regional distribution. It visualizes key insights, identifies trends, and supports data-driven understanding of platform content strategy.


# 📘 Project Summary

This project performs an in-depth Exploratory Data Analysis (EDA) on the Amazon Prime Video dataset. The goal is to understand the structure and characteristics of the platform’s content library, which includes both movies and TV shows. Through this analysis, we uncover patterns related to content type, genre popularity, rating distribution, release year trends, and regional availability.

🎯 Problem Statement

The Amazon Prime Video dataset provides an excellent opportunity to study the diversity and evolution of content available on the platform. This analysis helps answer key questions such as:

1. Content Diversity

Understanding which genres and categories dominate Amazon Prime Video is essential for strategic decision-making. By analyzing genre frequency, we can identify what types of content the platform prioritizes and how well it caters to different audience segments.

2. Trends Over Time

The entertainment industry evolves constantly. By examining how content distribution changes across years, we gain insights into Amazon Prime’s shifting focus—whether it leans toward shorter films, longer series, specific genres, or certain regions in response to market demand.

3. IMDb Ratings & Popularity

IMDb and TMDb ratings offer insights into viewer satisfaction and engagement. Analyzing these metrics helps identify high-performing titles, spot content gaps, and understand how ratings vary across genres, regions, and release years.

🛠️ Data Wrangling

To prepare the dataset for analysis, several preprocessing steps were performed:

Data Loading & Merging
The datasets titles.csv and credits.csv were imported and merged using the common column id.

Handling Missing Values

Missing values in the description and imdb_id columns were removed.

Missing age_certification entries were filled using the mode.

Missing values in seasons, imdb_votes, and character were replaced with 0, 0, and "unknown" respectively.

Missing values in imdb_score, tmdb_popularity, and tmdb_score were replaced with their column means.

Handling Duplicates
Duplicate records were identified and removed to ensure clean and reliable data.

📊 Data Visualization

To extract meaningful insights, several visualization techniques were applied:

• Univariate Analysis

Used to understand the distribution of individual variables such as:

IMDb scores

Runtime

Release year

Genre popularity
Techniques included histograms, box plots, and bar charts.

• Bivariate Analysis

Explored relationships between pairs of variables, such as:

IMDb votes vs. IMDb score

Line plots and scatter plots helped identify correlations and trends.

• Multivariate Analysis

Pairwise relationships between multiple variables were visualized using:

Pair plots

# Conclusion

This Exploratory Data Analysis (EDA) of the Amazon Prime Video dataset reveals several meaningful trends that highlight how the platform curates and distributes its content.

- Movies significantly outnumber TV shows, demonstrating Amazon Prime Video’s strong emphasis on film-based content. This suggests a strategy focused on offering a wide variety of quick-watch entertainment options to its global audience.

- Drama and Comedy dominate the genre distribution, indicating audience preference for emotionally engaging and light-hearted narratives. At the same time, the presence of numerous niche genres reflects the platform’s intent to appeal to diverse viewer segments.

- A gradual decline in movie runtimes contrasts with an increase in the number of TV show seasons, hinting at evolving storytelling formats—shorter films for faster consumption and longer series to retain viewer engagement over time.

- Higher ratings for older titles (both IMDb and TMDb) suggest that classic content continues to hold strong appeal. This may stem from nostalgic value, established audience trust, or the higher curation standards applied to older, well-received productions.

- The United States leads content creation, followed by India and the United Kingdom, emphasizing how these regions significantly shape the platform’s global catalog. This distribution also aligns with strong entertainment industries and growing streaming markets in these countries.

Overall, this EDA uncovers clear patterns in content distribution, audience engagement, and rating behavior. These insights can guide content acquisition teams, marketing strategists, data analysts, and creators in making informed decisions about what types of content resonate most. Future analyses—such as sentiment studies, genre-based performance evaluation, or user-behavior prediction—could further deepen understanding and support more effective platform strategies.

