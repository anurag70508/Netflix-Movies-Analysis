# 🎬 Netflix Movies Analysis

A complete **Exploratory Data Analysis (EDA)** project on a Netflix Movies dataset using **Python, Pandas, Matplotlib, and Seaborn**. This project focuses on cleaning the dataset, transforming data types, analyzing movie trends, and uncovering meaningful insights through data visualization.

---

## 📌 Project Overview

The objective of this project is to perform end-to-end exploratory data analysis on a movie dataset to understand:

* Movie popularity trends
* Genre distribution
* Rating patterns
* Release year analysis
* Vote count and vote average relationships
* Data cleaning and preprocessing techniques

This project demonstrates practical data analytics skills commonly used in real-world business and data science projects.

---

## 📂 Dataset

The dataset contains information about movies, including:

* 🎥 Title
* 📅 Release Year
* ⭐ Vote Average
* 🗳️ Vote Count
* 🎭 Genre
* 🔥 Popularity
* 📝 Overview
* 🌐 Original Language
* 🖼️ Poster URL

During preprocessing, unnecessary columns were removed and data types were transformed to improve analysis.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📊 Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Displayed sample records
* Inspected dataset structure

### 2. Data Exploration

* Checked dataset dimensions
* Examined column data types
* Generated descriptive statistics
* Verified missing values
* Identified duplicate records

### 3. Data Cleaning

* Converted `Release_Date` to Year format
* Removed unnecessary columns:

  * Overview
  * Original_Language
  * Poster_URL
* Prepared data for analysis

### 4. Feature Engineering

* Categorized **Vote Average** into four groups:

  * Not Popular
  * Below Average
  * Average
  * Popular

### 5. Exploratory Data Analysis (EDA)

Performed analysis on:

* Movie release trends over the years
* Genre distribution
* Popularity analysis
* Vote average distribution
* Vote count analysis
* Relationship between popularity and ratings
* Category-wise movie analysis

### 6. Data Visualization

Created informative visualizations using Matplotlib and Seaborn, including:

* Count plots
* Histograms
* Bar charts
* Distribution plots
* Comparative visualizations

---

## 📈 Key Insights

* Identified trends in movie releases over time.
* Explored how popularity varies across different genres.
* Analyzed the distribution of movie ratings.
* Categorized movies based on vote averages for better interpretation.
* Cleaned and transformed raw data into an analysis-ready format.

---

## 📁 Project Structure

```text
Netflix-Movies-Analysis/
│
├── Netflix Movies Analysis.ipynb
├── mymoviedb.csv
├── README.md
└── images/                
```

## 🎯 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Data Transformation
* Statistical Analysis
* Python Programming
* Business Insight Generation

---

## 🚀 Future Improvements

* Build an interactive Power BI dashboard
* Perform sentiment analysis using movie overviews
* Develop a movie recommendation system
* Create an interactive dashboard using Plotly or Streamlit
* Apply machine learning models for popularity prediction

---

## 🤝 Connect

If you found this project useful, consider giving the repository a ⭐ and feel free to connect for discussions on **Data Analytics**, **Machine Learning**, and **Data Visualization**.
