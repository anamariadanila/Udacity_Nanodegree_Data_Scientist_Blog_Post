# 📌 Data Science Salary Analysis (StackOverflow 2025)

## 📘 About This Project
This project analyzes how factors such as professional experience, job role, education level, geographic region, and work arrangement (remote, hybrid, in-person) influence salaries among tech professionals across Europe. The analysis follows the CRISP-DM framework, including data exploration, cleaning, feature engineering, modeling, and interpretation.
## 🎯 Project Overview
The goal of this project is to answer three key business questions:
1.	How do salaries differ between traditional Software Developers and Data/AI professionals?
2.	How does the work arrangement (remote, hybrid, in-person) influence salary levels?
3.	Which factors have the strongest impact on salary?
To address these questions, two machine learning models were applied:
-	Linear Regression for interpretability
-	Random Forest for capturing nonlinear relationships

## 🌟 Motivation
The European tech landscape is rapidly evolving, with salaries varying significantly based on skills, experience, and flexibility in work arrangements. This project aims to provide a data-driven understanding of salary trends for 2025, helping both professionals and organizations make more informed decisions regarding career development, compensation, and workforce planning.

## 📂 Data Source
The primary data used in this project comes from the:

📌 StackOverflow Developer Survey 2025

Official dataset available here:

👉 [Developer Survey](https://survey.stackoverflow.co/) 

Preprocessing steps included:
- filtering respondents to European countries
- handling missing values
-	standardizing and grouping categorical variables
-	mapping DevType, EdLevel, and OrgSize into broader categories
-	addressing outliers in compensation values
-	encoding features for machine learning models

## 🔍 Key Insights
📌 1. Data & AI professionals consistently earn higher salaries than traditional Software Developers across all experience levels.

📌 2. Remote work is associated with higher salaries, especially in Western and Northern Europe.

📌 3. The strongest predictors of salary are:
-	professional experience (WorkExp)
-	geographic region (EuropeRegion)
-	education level
-	work arrangement
-	job category (DevType)
  
📌 4. Linear Regression achieved an R² ≈ 0.37, while Random Forest reached an R² ≈ 0.35, indicating that salary is influenced by many complex and external factors that are difficult to capture fully with standard ML models.

## ⚙️ How to Run This Project
1. Clone the repository

```bash
git clone https://github.com/<username>/Udacity_Nanodegree_Data_Scientist_Blog_Post.git
cd Udacity_Nanodegree_Data_Scientist_Blog_Post 
```

2. Create a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows 
```
3. Install dependencies

```bash
pip install -r requirements.txt 
```
4. Launch Jupyter Notebook

```bash
jupyter notebook 
```
5. Run the notebook
Open:

Project_1.ipynb
and execute all cells in order.

## 📝 Blog Post
A detailed summary of this project is available on the blog:
👉 [Check it here](https://medium.com/@anamaria1616d/what-drives-tech-salaries-in-europe-in-2025-cf1603406fd6?postPublishedType=initial)

