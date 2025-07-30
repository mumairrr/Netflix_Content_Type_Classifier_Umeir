# 🎬 Netflix Content Type Classifier (EDA + ML) — by Umeir

This project explores and analyzes Netflix's titles dataset to uncover content trends through data cleaning, visual insights, and machine learning.  
In the final stage, a model predicts whether a title is a **Movie or TV Show** based on specific features.

---

## 📂 Table of Contents

1. [Introduction](#1-introduction)  
2. [Data Cleaning](#2-data-cleaning)  
3. [Exploratory Data Analysis (EDA)](#3-exploratory-data-analysis-eda)  
4. [Insights and Visualizations](#4-insights-and-visualizations)  
5. [Machine Learning - Predicting Movie vs TV Show](#5-machine-learning---predicting-movie-vs-tv-show)  
6. [Dataset](#dataset)  
7. [Tools & Libraries](#tools--libraries)  
8. [How to Run](#how-to-run)  
9. [Author](#author)

---

## 1. Introduction

Netflix offers a massive collection of titles ranging from TV Shows to Movies.  
The goal of this project is to:
- Understand the structure and trends in Netflix's content library
- Build a predictive model that classifies a title as a **Movie** or **TV Show** based on its duration, rating, and release year.

---

## 2. Data Cleaning

- Removed null and duplicate values
- Transformed `duration` column to numeric
- Encoded categorical columns (`type`, `rating`) for modeling

---

## 3. Exploratory Data Analysis (EDA)

- Analyzed distribution of Movies vs TV Shows  
- Examined content release trends over time  
- Investigated duration patterns and rating types

---

## 4. Insights and Visualizations

- Visual graphs to uncover patterns in ratings, content duration, and content type  
- Insights into trends in different regions and over different years  
- Found correlations between release year, content duration, and type

---

## 5. Machine Learning - Predicting Movie vs TV Show

A logistic regression model was trained on the following features:
- `duration_num`
- `rating_encoded`
- `release_year`

### Steps:
- Applied train/test split (80% training / 20% testing)
- Trained a **Logistic Regression** classifier
- Evaluated using Accuracy, Classification Report, and Confusion Matrix

**Model Accuracy:** 99.8%

---

## Dataset

- 📦 Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- Columns used: `type`, `duration`, `rating`, `release_year`

---

## Tools & Libraries

- **Python 3**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn**  
- **Jupyter Notebook**

---

## 🙋‍♂️ Author

**Umeir Mohamed**  
Master’s Student in Data Science – Milano Bicocca University  
[LinkedIn](https://www.linkedin.com/in/umeir-muhammad-shahzad/) | [GitHub](https://github.com/mumairrr)
