**📊Student Performance Analysis Dashboard Using PowerBI**

## 📌 Overview

The **Student Performance Analysis Dashboard** is an interactive **Power BI project** created to analyse and visualize the academic performance of students.

The dashboard is built using a single data table named **StudentData** and presents important academic information such as **grades, result categories, parental education, study hours, attendance, and total scores**.

The project transforms raw student data into meaningful visual insights through interactive charts, cards, and DAX-based calculations.

---

## 🎯 Objectives

* Analyse overall student academic performance.
* Understand student grades and result categories.
* Analyse the impact of attendance and study hours on performance.
* Visualize parental education levels.
* Analyse total scores of students.
* Present academic information through an interactive dashboard.
* Make student performance data easier to understand.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Data Modelling**
* **Data Visualization**

---

## 📊 Dashboard Features

The dashboard provides visual analysis of:

* 📈 Total Scores
* 🎓 Student Grades
* 📋 Result Categories
* 🕐 Study Hours
* 📅 Attendance
* 👨‍👩‍👧 Parental Education Level
* 📊 Student Performance

The dashboard is designed as a **single-page interactive report**, allowing users to understand different aspects of student performance in one place.

---

## 📂 Dataset

The project uses a single table:

**Table Name:** `StudentData`

The table contains information related to students' academic performance and other factors used for analysis.

### Main Attributes

* Grades
* Result Category
* Parental Education
* Study Hours
* Attendance
* Total Score

Add 1 column name as index direct in PowerBI. that is grade but convert into number form, like Grade A=1, Grade B=2,......, Grade E=5.

---

## Dashboard Architecture
The dashboard contains one interactive page, Page 1, designed on a 1920 × 1080 canvas. A header banner holds the title, and the navy panel below holds the slicer, KPI cards, and charts.
4.1 Page Layout
The page is arranged in three zones:
•	Left column: the Department slicer at the top and the Grade-Wise Student Count donut chart below it.
•	Top centre and right: four KPI cards and the Student Distribution by Grade and Result Category column chart.
•	Bottom centre and right: the Student Result Category by Parents Education Level bar chart and the Grade Performance and Engagement scatter chart.
Slicer
•	Department, displayed as a vertical list of selectable tiles that filters every visual on the page.
KPI Cards
•	Average Total Score
•	Overall Pass Rate
•	Best Performing Grade
•	Worst Performing Grade
Charts and Visuals
1. Donut chart – Grade-Wise Student Count.
2. Clustered column chart – Student Distribution by Grade and Result Category.
3. 100% stacked bar chart – Student Result Category by Parents Education Level.
4. Scatter chart – Grade Performance and Engagement (average attendance versus average total score, sized by study hours).


## 🔄 Project Workflow

StudentData Dataset
        ↓
Data Import into Power BI
        ↓
Data Cleaning & Preparation
        ↓
Data Modelling
        ↓
Create DAX Measures
        ↓
Calculate Key Performance Indicators
        ↓
Create Interactive Visualizations
        ↓
Add Department Filter/Slicer
        ↓
Build Single-Page Dashboard
        ↓
Analyse Student Performance

---

## 📐 DAX

DAX measures are used to perform calculations and generate meaningful metrics from the student data.

These measures help display calculated values such as **total scores and other performance-related indicators** within the dashboard.

---

## 📈 Dashboard Insights

The dashboard helps users:

* Understand the distribution of student grades.
* Compare different result categories.
* Examine attendance and study-hour patterns.
* Analyse parental education levels.
* Review total student scores.
* Identify patterns in academic performance.

---

## 📊 Dashboard
<img width="1167" height="657" alt="dashboard ss" src="https://github.com/user-attachments/assets/fb3d0bce-670e-4a51-9ca7-ed245a174206" />


## 📁 Project Files

```text
Student-Performance-Analysis-Dashboard/
│
└── README.md
├── Shravani61 PBI Project.pbix
└── StudentData.csv
```

### `.pbix` File

The `Shravani61 PBI Project.pbix` file contains the complete Power BI report, including the dataset, data model, DAX measures, and dashboard visualizations.

---

## 🚀 How to Use

1. Download or clone this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open Shravani61 PBI Project.pbix in Power BI Desktop.
4. Select one or more departments in the Department slicer to filter the page.
5. Read the KPI cards for the headline figures of the selection.
6. Click a grade, category, or bar in any chart to cross-filter the other visuals, and click it again to clear the selection.
7. Hover over a chart element to see its exact value in the tooltip.
Note: the file was saved with a Department filter applied, so the values shown on first opening reflect that selection. Clear the slicer to see all departments.
---

# What the Dashboard Helps to Show
The dashboard is designed to help the viewer answer questions such as:
•	What is the average total score and the overall pass rate for the selected department?
•	Which grade performs best and which performs worst?
•	How many students fall into each grade and each result category?
•	Does a higher parents’ education level go with better student results?
•	Do grades with higher attendance or more study hours also have higher average scores?
The actual values depend on the data and on the Department selection, and should be read from the live report in Power BI Desktop. This document does not state findings that were not read from the data.


## 🎓 Project Purpose

This project was developed as an academic **Data Science / Business Intelligence project** to demonstrate practical knowledge of data visualization, Power BI, DAX, and data analysis.

---

## 👩‍💻 Author

**Shravani Warang**

Data Science Student

---

## ⭐ Conclusion

The **Student Performance Analysis Dashboard** presents academic information on a single interactive page. KPI cards give the headline results, the donut and column charts show how students are spread across grades and result categories, the stacked bar chart links results to parental education, and the scatter chart compares grades by attendance, study hours, and average score. The Department slicer and cross-filtering let the viewer explore the data, and the dark gradient design keeps the page clear and consistent.


