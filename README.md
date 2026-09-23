# Global Freelancers - Excel Data Analysis

## Project Overview

This project is an Excel-based data cleaning and exploratory analysis exercise using a dataset of 1,000 freelancers.

The goal was to practice transforming inconsistent raw data into analysis-ready data, summarizing the results using PivotTables and presenting relevant information through an Excel dashboard.

The workbook contains three main sheets:

- **Data** - raw data alongside cleaned and standardized fields.
- **Pivots** - PivotTables used to summarize and explore the cleaned data.
- **Dashboard** - charts created from the PivotTable results.

## Data Cleaning

The original dataset contains several fields with inconsistent formats. The cleaning process includes:

- Removing titles and prefixes from freelancer names where necessary.
- Standardizing gender values into consistent categories.
- Grouping years of experience into ranges:
  - 0-5
  - 6-10
  - 11-15
  - 16-20
  - 21+
- Standardizing hourly rates represented in different formats, such as `$40`, `USD 75` and numeric values into numeric-only values.
- Standardizing active/inactive values into consistent categories.
- Normalizing customer satisfaction values for analysis.
- Preserving missing values where an appropriate replacement could not be justified.

## Data Analysis

PivotTables were used to explore:

- Average freelancer rating by primary skill.
- Distribution of freelancers by experience range.
- Distribution of hourly rates.
- Freelancer counts by language.
- Freelancer counts by country.

## Dashboard

An Excel dashboard was created to visualize the results of the analysis.

It includes:

- Average rating by primary skill.
- Freelancers by years of experience.
- Freelancers by hourly rate.
- Freelancers by language.
- Freelancers by country.

Horizontal bar charts are used for country and language data to improve the readability of category labels.

## Skills Practiced

- Microsoft Excel
- Data cleaning
- Data standardization
- Excel formulas
- Data type validation
- PivotTables
- PivotCharts
- Exploratory data analysis
- Dashboard creation
