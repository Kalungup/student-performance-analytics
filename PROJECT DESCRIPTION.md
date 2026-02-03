# Student Performance Analytics

<p align="center">
  <img src="https://raw.githubusercontent.com/Kalungup/student-performance-analytics/main/Abstract4all.png" width="90"/>
</p>

<h1 align="center">ABSTRACT 4 ALL</h1>

<p align="center">
Student Performance Analytics • Data Cleaning • Visualization • Insights
</p>

## 📌 Project Overview
This project performs data cleaning, exploratory data analysis (EDA), and visualization on a dataset of 10,000 student records containing academic marks and demographic information.  
The dataset intentionally contains errors to simulate real-world data quality challenges.

---

## 🎯 Objectives
- Clean messy real-world data
- Handle missing and incorrect values
- Standardize categorical data
- Perform exploratory data analysis
- Visualize patterns in student performance
- Prepare features for future machine learning

---

## 📂 Dataset
The dataset contains:

- 5 subjects: Maths, English, Science, History, ICT
- Demographics: Age, Gender, City, Parental Education, Attendance
- Intentional data issues:
  - Invalid marks (e.g. -10, 115, "absent")
  - Spelling errors in categories
  - Inconsistent formats
  - Outliers

📎 Dataset link:  
`student_marks_10000.csv`

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning Steps
- Converted subject columns to numeric
- Handled missing and invalid values
- Standardized categorical text
- Removed outliers
- Created new features (average score, pass/fail)

---

## 📊 Exploratory Data Analysis
- Subject performance comparison
- Gender vs performance
- Attendance vs marks
- City-wise performance
- Distribution of scores

---

## 📈 Visualizations
Key charts created to reveal patterns in performance and demographics.

---

## 🚀 How to Run

```python
import pandas as pd

url = "https://raw.githubusercontent.com/Kalungup/student-performance-analytics/main/student_marks_10000.csv"
df = pd.read_csv(url)
