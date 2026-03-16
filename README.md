# 🎬 Netflix Shows — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-EDA-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Overview
A comprehensive exploratory data analysis of Netflix's content library covering **~7,000 shows**. This project analyzes content distribution, director contributions, country-wise production, release trends, and audience rating patterns.

---

## 📂 Project Structure
```
netflix-analysis/
│
├── Netflix_data_analysis.ipynb  # Main analysis notebook
├── netflix_data.csv             # Dataset (add your own)
└── README.md
```

---

## 🔍 Key Questions Answered
- Are there more Movies or TV Shows on Netflix?
- Which directors contribute the most content?
- Which countries produce the most Netflix shows?
- What is the most common content rating?
- When did Netflix release the most content?
- What type of content dominated peak months?

---

## 📊 Key Findings

| # | Insight |
|---|---------|
| 1 | **Movies** significantly outnumber TV Shows on Netflix |
| 2 | The **United States** produces the most Netflix content globally |
| 3 | **TV-MA** is the most common content rating |
| 4 | **1-season** shows are the most common format |
| 5 | **Documentaries** are the most prevalent content type |
| 6 | Content peaked in **2018–2020**; 2019 was the highest year |
| 7 | **November 2019** was the single biggest release month |
| 8 | **Comedies** dominated November 2019 releases |

---

## 🛠️ Tools & Libraries
- **Python 3.10**
- **Pandas** — data manipulation and date parsing
- **NumPy** — numerical operations
- **Matplotlib** — bar charts, line plots, color maps
- **Seaborn** — statistical visualizations
- **IPython.display** — styled DataFrames

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sumitJoshi310/netflix-analysis.git
   cd netflix-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Add the dataset CSV to the project folder and update the path in Cell 2.

4. Launch Jupyter:
   ```bash
   jupyter notebook Netflix_data_analysis.ipynb
   ```

---

## 📁 Dataset
- Source: [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Records: ~7,000 titles
- Key columns: `Category`, `Director`, `Country`, `Rating`, `Duration`, `Type`, `Release_Date`

---

## 👨‍💻 Author
**Sumit Joshi** — Data Analyst  
[LinkedIn](https://www.linkedin.com/in/sumit-joshi-2059b828b) | [GitHub](https://github.com/sumitJoshi310)
