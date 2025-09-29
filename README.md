# CORD-19 Data Explorer

## Overview
This project provides a basic exploration and analysis of the **CORD-19 research dataset**, focusing on COVID-19 related research papers. The project includes:

- Data loading and cleaning
- Basic analysis and visualization
- An interactive Streamlit application for exploring the dataset

The goal is to gain hands-on experience with **data manipulation**, **visualization**, and **interactive dashboards** using Python.

## Dataset
- **Source:** [CORD-19 Research Challenge on Kaggle](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)
- **File used:** `metadata.csv`
- **Contents:** 
  - Paper titles and abstracts
  - Publication dates
  - Authors and journals
  - Source information

> Note: For this assignment, only the `metadata.csv` file or a sampled subset is used to simplify processing.

## Tools and Libraries
- **Python 3.7+**
- **pandas** — for data loading, cleaning, and analysis
- **matplotlib / seaborn** — for visualizations
- **Streamlit** — for building an interactive web application
- **Jupyter Notebook** (optional) — for exploratory data analysis

## Tasks Completed

### 1. Data Loading and Exploration
- Loaded the dataset using `pd.read_csv()`
- Inspected the first few rows using `.head()`
- Checked dataset dimensions, column types, and missing values
- Generated basic statistics for numerical columns

### 2. Data Cleaning and Preparation
- Handled missing values by removing or filling where appropriate
- Converted publication dates to datetime objects
- Extracted year from publication date for time-based analysis
- Created additional columns (e.g., abstract word count) for analysis

### 3. Data Analysis and Visualization
- Counted papers by publication year
- Identified top journals publishing COVID-19 research
- Analyzed most frequent words in paper titles
- Visualizations include:
  - Bar chart of publications by year
  - Bar chart of top journals
  - Word cloud of paper titles
  - Distribution of paper counts by source

### 4. Streamlit Application
- Built a simple interactive app to explore the dataset
- Features include:
  - Title and description
  - Year range slider
  - Dropdowns for filtering by journals or sources
  - Display of visualizations based on user selections
  - Data sample preview

### 5. Documentation and Reflection
- Code is commented for clarity
- Reflections on data challenges and insights gained

## How to Run
1. Install required packages:
```bash
pip install pandas matplotlib seaborn streamlit
