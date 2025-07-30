# 📊 Netflix EDA Project

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset. The goal is to uncover trends, patterns, and insights in the content available on the platform.

---

## 📁 Dataset

- Source: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Contains information like:
  - Type (Movie or TV Show)
  - Title, Director, Cast
  - Country of origin
  - Release year, Date added to Netflix
  - Duration, Rating, and Genre

---

## 🧹 Data Cleaning

- Removed null and duplicate values
- Normalized inconsistent country entries
- Converted date fields to datetime format
- Split multi-country fields for better analysis

---

## 📊 Key Insights

- Distribution of Movies vs. TV Shows
- Top countries producing Netflix content
- Most common genres and ratings
- Release trends over the years

---

## 📌 Visualizations

- Bar plots for type and country distribution
- Time-series plots for content added over the years
- Heatmaps for correlations

## Sample Visualization

![Top 10 Genres](top_genres_chart.png)
---

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn for data visualization
- Jupyter Notebook (Google Colab)

---

## 🙋‍♂️ Author

**Umeir Mohamed**  
Master’s Student in Data Science – Milano Bicocca University  
[LinkedIn](https://www.linkedin.com/in/umeir-muhammad-shahzad/) | [GitHub](https://github.com/mumairrr)

---

## 📦 Future Work

- Build a Machine Learning model to predict content type
- Add dashboard visualizations with Plotly or Tableau
