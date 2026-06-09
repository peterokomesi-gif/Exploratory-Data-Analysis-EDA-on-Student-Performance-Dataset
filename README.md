# Exploratory-Data-Analysis-EDA-on-Student-Performance-Dataset
This project performs Exploratory Data Analysis (EDA) on a Student Performance dataset using Python, Pandas, Matplotlib &amp; Seaborn. It explores grade distributions, correlations, attendance, study habits, internet access, and other factors affecting academic performance through statistical analysis  visualizations to generate actionable insights
# Exploratory Data Analysis (EDA) on Student Performance Dataset

##  Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Student Performance Dataset to uncover meaningful insights, trends, patterns, and relationships affecting academic performance. The analysis aims to understand factors that influence students' final grades and identify potential data quality issues before further modeling or decision-making.

The project follows a structured data analytics workflow including data cleaning, data exploration, statistical analysis, hypothesis testing, and data visualization.

Dashboard URL Link

https://studentsperformancedashboard.netlify.app/

---

##  Objectives

* Explore the structure and characteristics of the dataset.
* Understand the distribution of student grades and performance metrics.
* Identify trends, patterns, and anomalies within the data.
* Investigate relationships between academic performance and various student attributes.
* Test hypotheses using statistical analysis and visualization.
* Detect missing values, duplicates, and outliers.
* Generate actionable insights based on the findings.

---

##  Dataset Description

The dataset contains information about students' demographic, social, and academic characteristics.

### Key Features

| Feature   | Description                   |
| --------- | ----------------------------- |
| school    | Student's school              |
| sex       | Gender of student             |
| age       | Student age                   |
| address   | Urban or rural residence      |
| famsize   | Family size                   |
| Pstatus   | Parent cohabitation status    |
| Medu      | Mother's education level      |
| Fedu      | Father's education level      |
| studytime | Weekly study time             |
| failures  | Number of past class failures |
| internet  | Internet access at home       |
| absences  | Number of school absences     |
| G1        | First period grade            |
| G2        | Second period grade           |
| G3        | Final grade                   |

---

##  Research Questions

The analysis aims to answer the following questions:

1. How are final grades (G3) distributed?
2. How many students scored zero in the final examination?
3. Is there a strong relationship between G1, G2, and G3 grades?
4. Does internet access at home affect student performance?
5. Does study time influence final grades?
6. What is the impact of absences on academic performance?
7. Do students with previous failures perform worse?
8. How does parental education affect student outcomes?

---

##  Technologies Used

* Python
* Jupyter Notebook / Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

##  Project Structure

```text
Student-Performance-EDA/
│
├── data/
│   └── student-mat.csv
│
├── notebooks/
│   └── Student_Performance_EDA.ipynb
│
├── images/
│   ├── grade_distribution.png
│   ├── correlation_heatmap.png
│   ├── internet_vs_grades.png
│   └── absences_vs_grades.png
│
├── reports/
│   └── EDA_Report.pdf
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-performance-eda.git
```

Navigate into the project folder:

```bash
cd student-performance-eda
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Or open the notebook in Google Colab and run all cells sequentially.

---

## Analysis Performed

### Data Exploration

* Dataset shape and dimensions
* Data types inspection
* Missing value analysis
* Duplicate record detection

### Descriptive Statistics

* Summary statistics
* Distribution analysis
* Central tendency and dispersion measures

### Data Visualization

* Histograms
* Boxplots
* Countplots
* Scatter plots
* Correlation heatmaps
* Bar charts

### Hypothesis Testing

* Internet access vs academic performance
* Study time vs final grades
* Absences vs final grades

### Correlation Analysis

* G1 vs G2
* G2 vs G3
* G1 vs G3

---

## Key Findings

* Strong positive correlation exists between G1, G2, and G3 grades.
* Students with higher study time generally perform better.
* Increased absences are associated with lower final grades.
* Students with internet access tend to achieve slightly higher academic performance.
* Previous academic failures negatively impact final grades.
* Parental education level shows a moderate influence on student achievement.

---

##  Sample Visualizations

### Distribution of Final Grades (G3)

* Identifies grade spread and overall performance trends.

### Correlation Heatmap

* Highlights relationships between numerical variables.

### Internet Access vs Final Grades

* Compares academic performance based on home internet availability.

### Absences vs Final Grades

* Shows the relationship between attendance and academic outcomes.

---

##  Business and Educational Insights

The findings can help:

* Schools identify at-risk students early.
* Educators understand factors affecting performance.
* Parents support effective study habits.
* Institutions make data-driven academic decisions.

---

##  Future Improvements

* Build predictive models for student performance.
* Develop interactive dashboards using Power BI or Streamlit.
* Apply machine learning algorithms for grade prediction.
* Conduct feature importance analysis.
* Perform advanced statistical testing.

---

##  Learning Outcomes

Through this project, the following skills were developed:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Hypothesis Testing
* Insight Generation
* Python Programming

---

##  Author

**Your Name**
Peter Okomesi

Data Analytics Intern

---

##  License

This project is licensed under the MIT License.
