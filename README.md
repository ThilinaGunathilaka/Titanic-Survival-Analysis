# 🚢 Titanic Survival EDA Project

This project is an Exploratory Data Analysis (EDA) of the famous Titanic dataset. The goal is to analyze which factors — such as **passenger class**, **gender**, **age**, and more — affected survival rates.

## 🎯 Project Objective

To improve data science skills by:
- Practicing data cleaning and wrangling using **Pandas**
- Visualizing patterns using **Seaborn**
- Drawing insights from real-world data

## 📁 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- File Used: `train.csv`

## 🛠️ Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib

## 📊 Steps Performed

### 1. Load and Inspect Data
- Viewed structure, column types, missing values, and distributions

### 2. Clean the Data
- Filled missing `Age` with median
- Filled missing `Embarked` with mode
- Dropped `Cabin`, `Ticket`, and `Name` columns

### 3. Explore and Visualize Features
- Distribution plots for `Age` and `Fare`
- Count plots for `Sex`, `Pclass`, and `Embarked`

### 4. Analyze Survival Rates
- Compared survival rates by:
  - **Gender**
  - **Class**
  - **Age Group**
  - **Embarkation Port**
- Used grouped statistics and barplots

### 5. Correlation Analysis
- Created a heatmap of numerical feature correlations
- Observed relationships between survival and features like `Sex`, `Fare`, and `Pclass`

## 📈 Key Findings

- **Women** and **1st class passengers** had the highest survival rates
- **3rd class men** had the lowest survival rates
- **Children** had slightly higher survival chances
- Higher **fare** was positively correlated with survival

## 📌 Future Work

- Apply basic machine learning models to predict survival
- Try feature engineering (e.g., family size, titles from names)
- Build a dashboard using Plotly or Streamlit

## 🙌 Acknowledgements

- Thanks to Kaggle for the Titanic dataset
- Inspired by classic beginner data science projects

---

🧠 *This project was built to strengthen my data science skills through hands-on analysis and visualization. Feel free to fork or contribute!*
