# Eye Cancer Patients Analysis

This project analyzes a dataset of eye cancer patients to understand survival outcomes, treatment effects, and demographic patterns using Python (Pandas, Matplotlib, Seaborn).

## 🔍 Dataset Overview

The dataset contains medical information on 5,000 patients including:

- Age, Gender, Country
- Cancer Type, Stage, Laterality
- Date of Diagnosis, Genetic Markers, Family History
- Treatment Types: Surgery, Chemotherapy, Radiation
- Outcome Status and Survival Time

## 🧹 Data Processing

- Converted diagnosis dates into datetime format
- Engineered new features:
  - `Treatment_Received`: Whether any treatment was given
  - `Survival_Category`: Grouped survival time into bins

## 📊 Visualizations

- Cancer Type Distribution
- Survival Time Histogram
- Bar Chart: Average Survival by Treatment
- Heatmap: Feature Correlations

## 🚀 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
