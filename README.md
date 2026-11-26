# Netflix Content Trend – Mini Data Warehouse & Analytics

## Project Overview

This project focuses on building a mini data warehouse for Netflix content analysis through data integration, data cleaning, API enrichment, and ETL processes.

## Data Sources

| Source | Description |
|---|---|
| [Netflix Dataset](https://www.kaggle.com/datasets/paramvir705/netflix-dataset) | Netflix movies and TV shows metadata |
| [IMDb Dataset](https://www.kaggle.com/datasets/ashirwadsangwan/imdb-dataset?select=title.basics.tsv) | Additional title information |
| [TMDB API](https://developer.themoviedb.org/) | Enrichment of missing director information |

## ETL Pipeline

- **Extract:** Collect data from Netflix, IMDb, and TMDB API.
- **Transform:** Clean, preprocess, and integrate data from multiple sources.
- **Load:** Organize processed data into fact and dimension tables.

## Data Warehouse Design

The project uses dimensional modeling with fact and dimension tables to support Netflix content analysis.

## Tools & Technologies

- Python
- Pandas
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
README.md
```
