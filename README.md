# Netflix Content Analysis

## Overview

This project analyzes the Netflix titles dataset to explore the composition, geographic distribution, genres, ratings, duration, and content additions over time.

## Objectives

- Analyze the distribution of Movies and TV Shows.
- Examine content additions over time.
- Identify countries with the largest representation.
- Analyze the most common genres.
- Explore content ratings.
- Analyze movie and TV show duration.
- Generate key insights and recommendations.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis

The project includes:

- Data inspection
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Geographic analysis
- Genre analysis
- Content rating analysis
- Duration analysis
- Trend analysis

## Key Visualizations

### Netflix Catalog Composition

Netflix Catalog Composition - (images/catalog_composition.png)

### Content Added Over Time

Content Added Over Time - (images/content_added_over_time.png)

### Top 10 Countries by Number of Titles

Top 10 Countries - (images/top_countries.png)

### Top 10 Genres by Number of Titles

Top 10 Genres - (images/top_genres.png)

### Content Ratings

Content Ratings - (images/content_ratings.png)

### Movie and TV Show Duration

Content Duration - (images/content_duration.png)

### Movies vs. TV Shows Over Time

Movies vs. TV Shows Over Time - (images/movies_vs_tv_shows_over_time.png)

## Key Insights

### 1. Catalog composition
Netflix's catalog leans heavily toward movies (69.6%) over TV shows (30.4%), suggesting a historical strategy favoring single-format content over episodic series.

### 2. Growth and slowdown
Content additions peaked in 2019, followed by a decline in 2020 and 2021. The dataset alone does not establish the cause of this decline, so external factors would need to be investigated separately.

### 3. Geographic concentration
The United States dominates the catalog with 3,689 titles, followed by India (1,046) and the United Kingdom (804). This shows that, despite being a global platform, content remains heavily concentrated in specific markets, with the U.S. representing a disproportionately large share compared to the other 127 countries present.

### 4. Predominant genres
"International Movies," "Dramas," and "Comedies" lead the catalog. The strong presence of "International Movies" (2,752) reflects an effort to diversify content beyond purely U.S. productions, although the country-level data shows that this diversity is still limited in actual volume.

### 5. Audience rating
TV-MA is the most common rating (3,207 titles), indicating that the catalog skews mostly toward mature/adult audiences, well above family or children's content (TV-Y, TV-G, G combined account for far fewer titles).

### 6. Duration
Movies have a median runtime of 98 minutes (ranging from 3 to 312 min), consistent with industry standards. TV shows, on the other hand, tend to have few seasons: the median is just 1 season, suggesting Netflix favors limited formats (miniseries or short-run shows) over long-running series.

### 7. Data quality
The director column has the highest percentage of missing values (29.91%), followed by country (9.44%) and cast (9.37%). This is worth noting as it limits deeper analysis around directors or casting, and should be mentioned as a dataset limitation.

## Recommendations

### Evaluate TV Show Season Length
Most TV Shows in the dataset have only 1–2 seasons. Netflix could investigate whether this pattern is driven by content strategy, miniseries formats, or early cancellations before deciding whether longer-running series should be prioritized.

### Diversify the catalog by country:
The strong concentration in the United States, India, and the United Kingdom leaves room for growth in underrepresented markets, especially if the platform aims to expand in regions like Latin America or Africa, where title volume is considerably lower.

### Evaluate the rating balance:
With TV-MA dominating the catalog, expanding content offerings for younger audiences (TV-Y7, TV-G) could help attract family-oriented subscribers, a segment currently underserved based on the data.

### Improve data integrity for future versions:
The near-30% absence of values in director limits analysis related to creative talent. At the data collection level, it's recommended to complete this information for more robust future analyses.

### Investigate the post-2019 decline: 
It would be worth cross-referencing this data with external factors (such as the pandemic) to understand whether the slowdown in content additions was a strategic decision or a consequence of factors outside the platform's control.

## Conclusion

This analysis shows that Netflix's catalog is heavily composed of Movies, with strong representation from the United States and a significant presence of International Movies, Dramas, and Comedies.

Content additions increased substantially until 2019 before declining in the following years. The catalog also contains a large proportion of mature-rated content, while most TV Shows have relatively few seasons.

Overall, the analysis highlights several patterns in Netflix's content strategy while also showing limitations in the dataset, particularly missing information related to directors, countries, and cast.