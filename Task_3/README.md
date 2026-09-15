# Exploratory Data Analysis Of Netflix

## Problem Statement

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to understand the data, identify trends and patterns, and find relationships between numerical variables.

## Dataset Details

The dataset contains information about movies and TV shows available on Netflix.

It contains **8,807 records and 12 columns**, including:

* Show ID
* Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Listed In
* Description

The dataset is stored in the project folder as `netflix_titles.csv`.

## Approach

The following steps were performed during the analysis:

1. Loaded the Netflix dataset using Pandas.
2. Checked the shape, data types, and basic information of the dataset.
3. Checked missing values in different columns.
4. Handled missing values by replacing them with `Unknown` where appropriate.
5. Performed summary statistics on the dataset.
6. Analyzed the distribution of Movies and TV Shows.
7. Identified trends in the number of titles by release year.
8. Compared Movies and TV Shows across different release years.
9. Performed correlation analysis between movie release year and movie duration.
10. Created graphs to support the findings.

## Results

Some important findings from the analysis are:

* The dataset contains **8,807 Netflix titles**, including **6,131 Movies** and **2,676 TV Shows**.
* Movies make up approximately **69.62%** of the dataset, while TV Shows make up approximately **30.38%**.
* The number of titles increased considerably in recent years.
* **2018** had the highest number of titles in the dataset, with **1,147 titles**.
* Movies had higher title counts than TV Shows for most recent years, but TV Shows exceeded Movies in **2021**.
* The correlation between `release_year` and `movie_duration` was **-0.206285**, indicating a weak negative relationship.
* Graphs such as count plots, bar charts, line charts, and scatter plots were used to support the analysis and findings.

## Tools and Libraries

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Files

```text
Synent_Task_3_Netflix_EDA/
│
├── netflix_titles.csv
├── Netflix_EDA.ipynb
└── README.md
```
