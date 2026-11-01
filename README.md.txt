# Diabetes Patient Data Engineering & Analysis

## Project Overview
This project focuses on data cleaning, preprocessing, feature engineering, and exploratory data analysis (EDA) using a diabetes patient dataset.

The goal is to transform raw healthcare data into a structured and analysis-ready dataset.

## Project Objectives
- Clean and preprocess raw data.
- Handle missing values and convert data types.
- Transform categorical variables.
- Perform feature engineering.
- Prepare data for further analysis.
- Explore patterns and relationships through visualizations.

## Data Engineering
The preprocessing workflow includes:
- Handling missing values.
- Converting data types.
- Creating new features, including total visits and age midpoint.
- Creating patient risk-related indicators.
- Applying One-Hot Encoding and binary encoding.

## Exploratory Data Analysis
The project includes visualizations such as:
- Readmission distribution.
- Gender vs. readmission analysis.
- Number of medications and hospital stay analysis.
- Correlation heatmap.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
```text
Diabetes-Patient-Data-Engineering-Analysis/
├── notebooks/
│   ├── data eng project.ipynb
│   └── Visualization2.ipynb
├── data/
│   └── diabetic_data.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebooks using Jupyter Notebook.
4. Make sure the dataset is available at the file path used in each notebook.

## Project Scope
This project focuses on data engineering, preprocessing, feature engineering, and exploratory data analysis. It does not include training a machine learning prediction model.
