# 🚀 Day 3 — Exploratory Data Analysis (EDA) on Titanic Dataset 🛳️

This project is part of my **30-Day Data Analysis + AI Challenge**.  
The focus for Day 3 was to explore, clean, and visualize the Titanic dataset to uncover hidden patterns and insights.

---

## 📌 Project Overview
The Titanic dataset is a classic dataset from [Kaggle](https://www.kaggle.com/c/titanic), containing details about passengers such as age, class, gender, and survival status.  
Our goal was to perform **EDA** to answer questions like:

- How did **passenger class** impact survival?
- Did **gender** play a significant role in survival rates?
- How did **age distribution** differ between survivors and non-survivors?
- Which **embarkation point** had the highest survival rate?

---

## 🔹 Key Steps

### 1. **Data Cleaning**
- Removed duplicates
- Handled missing values (Age, Embarked, Cabin)
- Converted categorical variables into proper types

### 2. **Descriptive Statistics**
- Calculated mean, median, mode, min, max for numerical columns
- Summarized categorical distributions

### 3. **Data Visualization**
- **Histograms** for age distribution
- **Countplots** for gender, class, embarkation
- **Heatmap** for correlation analysis
- **Boxplots** for class vs. fare distribution
- **Bar charts** for survival by multiple factors

### 4. **Insights**
- Females had a significantly higher survival rate
- First-class passengers survived more than third-class
- Younger passengers had better survival chances
- Passengers embarking from **Cherbourg** had a higher survival rate

---

## 🛠️ Tools & Libraries
- **Python**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Dataset**: Titanic (Kaggle)
