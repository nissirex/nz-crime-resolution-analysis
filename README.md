# nz-crime-resolution-analysis

## Overview
This project analyses New Zealand Police victimisation data to examine how crime resolution rates change over time across major offence categories.

Using R and the tidyverse ecosystem, the analysis explores investigation outcomes at 7, 30, 90, and 180 days for the most frequent ANZSOC divisions in New Zealand.

## Research Question
How do the proportions of resolved and unresolved cases change over time across the five most frequent ANZSOC divisions in New Zealand?

## Tools Used
- R
- tidyverse
- ggplot2
- data wrangling
- exploratory data analysis

## Analysis Steps
- Data cleaning and preparation of police victimisation records
- Identification of the five most frequent ANZSOC offence divisions
- Analysis of resolution outcomes at 7, 30, 90, and 180 days
- Visualisation of resolution trends across offence categories and years

## Key Findings
- Resolution rates increase as investigations progress over time.
- Offences involving harm to persons tend to have higher resolution rates than property crimes.
- Theft remains one of the least resolved offence categories even after 180 days.
- Long-term trends show little improvement in resolution rates across several offence categories.

## Project Structure

```
nz-crime-resolution-analysis/
│
├── analysis/
│ └── crime_resolution_analysis.Rmd
│
├── output/
│ └── nz_crime_resolution_analysis.pdf
│
└── README.md
```

## Data Source
The dataset used in this project is sourced from the New Zealand Police Data Portal.

Due to GitHub file size limitations, the full dataset is not included in this repository.

Download the dataset here:  
https://drive.google.com/file/d/1W8mcloNe7sF4EXCmTbgGAFqX7TTLraTk/view?usp=sharing

After downloading, place the dataset in the `data/` directory before running the analysis.

## How to Run
1. Open the R Markdown file in RStudio.
2. Install required packages:

```r
install.packages("tidyverse")
```
3. Knit the document to reproduce the analysis.
