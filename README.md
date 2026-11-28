# Netflix Content Trend – Mini Data Warehouse & Analytics

## Project Overview

An end-to-end data engineering and analytics project that integrates Netflix, IMDb, and TMDB data to build a mini data warehouse and analyze Netflix content trends using Python and Power BI.

## Data Sources

| Source | Description |
|---|---|
| [Netflix Dataset](https://www.kaggle.com/datasets/paramvir705/netflix-dataset) | Netflix movies and TV shows metadata |
| [IMDb Dataset](https://www.kaggle.com/datasets/ashirwadsangwan/imdb-dataset?select=title.basics.tsv) | Additional title information |
| [TMDB API](https://developer.themoviedb.org/) | Used to fill in missing director information |

## ETL Pipeline

- **Extract:** Collect data from Netflix, IMDb, and TMDB API.
- **Transform:** Clean, preprocess, and integrate data using RapidMiner.
- **Load:** Organize processed data into fact, dimension, and bridge tables.

## Data Warehouse Design

The data warehouse consists of:

- 2 Fact Tables
- 5 Dimension Tables
- 2 Bridge Tables

## Data Analysis

Analyzed 8,743 titles using Python to answer five business questions:

1. Which genres have the most content on Netflix?
2. Which countries produce the most content?
3. How have average TMDB scores changed over time?
4. Which directors have the most titles and what are their average scores?
5. How do runtime and genre relate to TMDB scores?

## Key Findings

| Metric | Result |
|---|---:|
| High Quality Content | 4.93% |
| Movie Content | 69.68% |
| Average TMDB Score | 6.25 |
| Runtime and Score Correlation | 0.1182 |

- Drama and Comedy are the most common genres.
- The United States has the most titles (3,662).
- Animation and Documentary have the highest average scores among the 10 analyzed genres.
- Movie runtime has a weak positive correlation with TMDB scores.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- RapidMiner
- REST API
- ETL
- Data Warehousing

## Project Structure

```text
ETL/
├── Extract.xml
├── clean.xml
├── Factf.xml
└── dimension.xml

API.ipynb
Netflix_Analytics.ipynb
README.md
```

## Data Availability

Processed datasets are not included due to potential data redistribution restrictions. Original data sources are provided above.

