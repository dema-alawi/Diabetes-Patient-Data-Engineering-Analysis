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
- Google Colab

## Project Structure

```text
Diabetes-Patient-Data-Engineering-Analysis/
├── data_eng_project.ipynb
├── Visualization2.ipynb
├── diabetic_data.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

### Using Google Colab
1. Open the notebook using Google Colab.
2. Upload the `diabetic_data.csv` dataset to the Colab session.
3. Run all cells in the notebook.

### Running Locally
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebooks using Jupyter Notebook.
4. Make sure the dataset path in each notebook points to the correct location.

## Project Scope
This project focuses on data engineering, preprocessing, feature engineering, and exploratory data analysis. It does not include training a machine learning prediction model.

## Dataset Source
The dataset used in this project is **Diabetes 130-US Hospitals for Years 1999–2008**, obtained from the UCI Machine Learning Repository.

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/296/diabetes+130-us-hospitals+for-years-1999-2008)
- **Authors:** Clore, J., Cios, K., DeShazo, J., & Strack, B. (2014).
- **DOI:** [10.24432/C5230J](https://doi.org/10.24432/C5230J)
- **License:** Creative Commons Attribution 4.0 International (CC BY 4.0).
