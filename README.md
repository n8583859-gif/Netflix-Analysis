# **Netflix Content Analysis**

---
---

A Python EDA project that explores Netflix’s content catalog using data cleaning, univariate analysis, bivariate analysis, and multivariate analysis.

This project was built to practice real-world data analysis workflow using Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

---

## *Project Objective*

The goal of this project is to understand:

- what kind of content Netflix has in its catalog
- how Movies and TV Shows differ
- which ratings, genres, countries, and years are most common
- how Netflix’s catalog has changed over time
- and many more understandings

---

## *Dataset*

**Source:** Netflix Titles dataset  
**Main file:** `analysis.ipynb`

The dataset contains information such as:

- title
- type
- director
- cast
- country
- date added
- release year
- rating
- duration
- listed genres
- description

---

## *Workflow Followed*

### 1. Data Understanding

- checked shape, columns, data types, duplicates, and missing values
- studied the structure of the dataset before cleaning

### 2. Data Cleaning

- handled missing values based on column importance and data type
- removed duplicate rows
- prepared the **major data** for analysis

### 3. Univariate Analysis

- analyzed one variable at a time
- studied content type, ratings, release year, countries, genres, duration, and date added

### 4. Bivariate Analysis

- analyzed relationships between two variables
- compared content type with ratings, countries, genres, and release trends

### 5. Multivariate Analysis

- analyzed three variables together
- explored deeper patterns across country, genre, rating, release year, and content type

---

## *Key Findings*

Some important patterns found in the dataset include:

- Netflix has more Movies than TV Shows.
- A few audience ratings dominate most of the catalog.
- The catalog is concentrated in recent years.
- A small number of countries contribute a large share of content.
- Genres differ across Movies and TV Shows.
- Duration patterns are different for Movies and TV Shows.
- Netflix’s catalog additions changed significantly over time.

---

## *Tech Stack*

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Data analysis
- Data visualization
- Data cleaning
- Data manioulation
- End to end workflow

---

## *Project Structure*

```text
Netflix_Analysis
│
├── dataset/
|   └── netflix_titles.csv
├── notebooks
|   └── analysis.ipynb
├── README.md
├── requirements.txt
├── images
|    └── charts
```
