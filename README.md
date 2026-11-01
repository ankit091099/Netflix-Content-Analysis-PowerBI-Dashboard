# Netflix Content Analysis Dashboard – Power BI

## Overview
A Power BI dashboard built on the Netflix titles catalog (`netflix_titles.csv`). It shows how the catalog splits between movies and TV shows, which content categories are most common, how titles are rated, and which countries and directors contribute most.

## Dashboard Visuals
| Visual | Chart type | What it shows |
|--------|-----------|----------------|
| Content Mix: Movies vs TV Shows | Pie chart | Share of Movies and TV Shows in the catalog |
| Most Popular Content Categories by Title Count | 100% stacked bar | Title count by `primary_category`, split by type |
| Directors by Rated Titles | 100% stacked column | Director counts across rating categories |
| Filter by Country | Slicer | Filters every visual by country |

## Data Preparation
- Source: `netflix_titles.csv`
- Cleaned and transformed in Power Query
- Created a `primary_category` column using a category mapping table, to group titles into main content categories

## Tools & Techniques
- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX
- Custom theme and branding (Netflix red)
- Slicers and cross-visual filtering

## Key Insights
(Add 3 to 4 findings here, for example: share of Movies vs TV Shows, the top content category, the most common rating, and the country with the most titles.)

## Dashboard Preview
![Dashboard](dashboard.png)

## How to Open
Download `INDUSTRIAL_PROJECT_2.pbix` and open it in Power BI Desktop (free from Microsoft).
