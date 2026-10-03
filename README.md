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

## 📁 Project Files

```text
Student-Performance-Analysis-Dashboard/
│
└── README.md
├── Shravani61 PBI Project.pbix
└── StudentData.csv
```

### `.pbix` File

The `.pbix` file contains the complete Power BI report, including the dataset, data model, DAX measures, and dashboard visualizations.

---

## 🚀 How to Use

1. Download or clone this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open the `.pbix` file.
4. Explore the interactive dashboard.
5. Use the available visualizations and filters to analyse student performance.

---

## 🎓 Project Purpose

This project was developed as an academic **Data Science / Business Intelligence project** to demonstrate practical knowledge of data visualization, Power BI, DAX, and data analysis.

---

## 👩‍💻 Author

**Shravani Warang**

Data Science Student

---

## ⭐ Conclusion

The **Student Performance Analysis Dashboard** demonstrates how Power BI can be used to transform raw student data into an interactive and easy-to-understand visual report. It provides a consolidated view of important academic indicators and helps users explore student performance through data-driven visualizations.


