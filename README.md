# Amazon Prime Video Data Analysis

## Overview
This project analyzes Amazon Prime Video content, including movies and TV shows, using a dataset containing metadata like genres, ratings, directors, and release years. The visual dashboard, created in Power BI, provides insights into content distribution, ratings, and trends over time.

## Dataset Information
- **File Name:** `amazon_prime_titles.csv`
- **Source:** Amazon Prime Video metadata
- **Key Columns:**
  - `Title` – Name of the movie or TV show
  - `Genre` – Categories such as Drama, Comedy, etc.
  - `Director` – Name of the director(s)
  - `Country` – Country of origin
  - `Release Year` – Year of release
  - `Rating` – Age-based classification (e.g., PG, R, 13+)
  - `Type` – Movie or TV show
  - `Duration` – Runtime in minutes or number of seasons

## Insights from Dashboard
1. **Total Content**:
   - 9,655 titles (both movies and TV shows)
   - 519 unique genres
   - 5,771 directors
   - Content spans from 1920 to 2021

2. **Genres Distribution**:
   - Drama is the most popular genre, followed by Comedy and Suspense.
   - Animation and Kids' content also have significant representation.

3. **Ratings Distribution**:
   - Most content falls under 13+, 16+, and ALL ratings.
   - R-rated and PG-13 content have moderate representation.

4. **Content by Country**:
   - Major contributions from North America and some European & Asian regions.

5. **Movies vs. TV Shows**:
   - 80.82% of the content consists of TV shows.
   - 19.18% are movies.

6. **Release Trends**:
   - A sharp increase in releases after 2000, with a peak in recent years.

## Tools Used
- **Power BI** for dashboard visualization
- **Python/Pandas** for data preprocessing
- **Microsoft Bing Maps** for geographic insights