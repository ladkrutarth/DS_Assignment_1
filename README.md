# DS_Assignment_1

# Principles of Data Science - Assignment 1

## Overview

This repository contains the solutions for Assignment 1 of the **Principles of Data Science** course. The assignment is divided into two parts:

1. **Frailty Analysis** - Designing a reproducible workflow for analyzing grip strength and frailty in female participants.
2. **Student Performance Visualization** - Performing five different data visualizations on the given student performance dataset.

---

## Question 1: Frailty Analysis

### Dataset:

The dataset consists of 10 female participants with the following attributes:

- **Height** (in inches)
- **Weight** (in pounds)
- **Age** (in years)
- **Grip Strength** (in kg)
- **Frailty** (Presence or Absence of symptoms)

### Reproducible Workflow Stages:

A well-structured workflow is essential for reproducibility. Below are the three stages along with the work involved and folder structure:

#### 1. **Raw Data and Collection**

- Folder: `data/raw/`
- Contains the original dataset.
- Work: Collecting and storing data in CSV format.

#### 2. **Data Processing and Cleaning**

- Folder: `data/processed/`
- Work: Cleaning data, handling missing values, and transforming it for analysis.

#### 3. **Analysis and Results**

- Folder: `results/`
- Work: Running statistical analysis, summarizing key insights, and generating reports.

**Folder Structure:**

```
frailty_analysis/
│── data/
│   ├── raw/
│   │   ├── frailty_data.csv
│   ├── processed/
│   │   ├── cleaned_data.csv
│── results/
│   ├── analysis_report.pdf
│── scripts/
│   ├── data_cleaning.py
│   ├── analysis.py
```

---

## Question 2: Student Performance Visualization

### Data Source:

[Student Performance Dataset](<Insert Data Link Here>)

### Visualization Tasks:

We will create five different visualizations to analyze student performance.

1. **Histogram of Scores** - Understand the distribution of student scores.
2. **Scatter Plot of Study Time vs. Scores** - Examine correlation between study time and performance.
3. **Box Plot of Scores by Gender** - Compare score distributions across genders.
4. **Bar Chart of Parental Education vs. Scores** - Analyze impact of parental education.
5. **Heatmap of Correlations** - Identify relationships among multiple variables.

### Folder Structure:

```
student_performance_visualization/
│── data/
│   ├── raw/
│   │   ├── student_data.csv
│   ├── processed/
│   │   ├── cleaned_student_data.csv
│── visualizations/
│   ├── histogram.png
│   ├── scatter_plot.png
│   ├── box_plot.png
│   ├── bar_chart.png
│   ├── heatmap.png
│── scripts/
│   ├── data_processing.py
│   ├── visualization.py
│── reports/
│   ├── visualization_report.pdf
```

---

## How to Use

1. Clone the repository.
2. Navigate to the respective folder (`frailty_analysis` or `student_performance_visualization`).
3. Run the scripts to generate results and visualizations.

```bash
git clone <repository_link>
cd assignment_1
python scripts/data_cleaning.py
python scripts/analysis.py
python scripts/visualization.py
```

---

## Dependencies

Ensure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn
```

---


