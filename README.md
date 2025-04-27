
# 🍽️ Zomato Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/) 
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)](https://pandas.pydata.org/) 
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A complete project involving **cleaning**, **analyzing**, and **visualizing** Zomato's restaurant data to extract valuable business insights.

---

## 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Technologies Used](#-technologies-used)
- [Project Workflow](#-project-workflow)
- [Dataset Details](#-dataset-details)
- [How to Run](#-how-to-run)
- [Key Insights](#-key-insights)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 🔥 Project Overview

This project aims to:

- Understand restaurant trends from Zomato data.
- Analyze factors affecting restaurant ratings and cost.
- Clean messy real-world data for effective analysis.

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **Matplotlib / Seaborn** (optional) - Visualization

---

## 🧩 Project Workflow

1. **Data Importing** 📥
   - Load `zomato.csv` dataset.
2. **Data Cleaning** 🧹
   - Drop irrelevant columns (e.g., `url`, `address`, `phone`).
   - Rename columns for clarity.
   - Handle missing values.
   - Remove duplicate entries.
   - Format rating data.
3. **Exploratory Data Analysis (EDA)** 🔎
   - Most popular cuisines.
   - Top-rated restaurants.
   - Cost analysis across cities.
   - Relation between rating and cost.
4. **Visualization (Optional)** 📊
   - Bar plots, pie charts, histograms, etc.

---

## 📁 Dataset Details

The dataset contains:

- Restaurant Name
- Online Order availability
- Book Table option
- Rating
- Approximate cost
- Cuisines served
- City and Restaurant type

Source: `zomato.csv`

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/zomato-data-analysis.git
   ```
2. Navigate to the directory:
   ```bash
   cd zomato-data-analysis
   ```
3. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## 📈 Key Insights

- **Most common cuisines:** North Indian, Chinese, etc.
- **Top cities:** Bangalore, Delhi, Mumbai dominate restaurant counts.
- **Cost Analysis:** Average cost for two varies heavily across cities.
- **Rating Trends:** Restaurants offering online orders tend to have higher ratings.


---

## 🎯 Future Enhancements

- Create a predictive model to forecast restaurant ratings.
- Build an interactive dashboard using Plotly or Tableau.
- Expand analysis to geographical mapping.

---

## 👩‍💻 Author

- **Your Name**  
  [GitHub Profile](https://github.com/aure-lius)

---

⭐ If you like this project, don't forget to star it!
