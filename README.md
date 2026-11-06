# Exploratory Data Analysis of Stroke Dataset

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a real-world Stroke Prediction Dataset obtained from Kaggle.

The main objective is to understand the dataset structure, identify missing values, examine numerical and categorical variables, and discover meaningful patterns and relationships associated with stroke.

The analysis is performed using Python, Pandas, NumPy, Matplotlib, and Seaborn.

## Dataset Information

- **Dataset Name:** Stroke Prediction Dataset
- **Source:** Kaggle
- **Author:** Fedesoriano
- **Total Records:** 5,110
- **Total Columns:** 12
- **Target Column:** `stroke`

**Original Kaggle Dataset:**  
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

### Dataset Features

| Column | Description |
|---|---|
| id | Unique patient identifier |
| gender | Gender of the patient |
| age | Age of the patient |
| hypertension | 0 = No, 1 = Yes |
| heart_disease | 0 = No, 1 = Yes |
| ever_married | Marriage status |
| work_type | Type of employment |
| Residence_type | Urban or Rural |
| avg_glucose_level | Average glucose level |
| bmi | Body Mass Index |
| smoking_status | Smoking history |
| stroke | 0 = No Stroke, 1 = Stroke |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Exploratory Data Analysis

The following steps were performed:

1. **Data Loading:** Loaded the Kaggle dataset using Pandas.
2. **Data Understanding:** Examined dataset shape, column names, data types, first and last records, memory usage, and summary statistics.
3. **Missing Value Analysis:** Identified missing values, calculated missing value percentages, and visualized missing values.
4. **Categorical Analysis:** Examined value counts of categorical variables.
5. **Data Cleaning:** Removed the unnecessary ID column and handled missing BMI values using gender-wise median imputation.
6. **Data Visualization:** Created visualizations to understand distributions and relationships between variables.

## Visualizations

Five main EDA visualizations were created:

1. **Age Distribution by Stroke Status** – Examines age distribution across stroke categories.
2. **Glucose Level Distribution by Stroke** – Compares average glucose levels across stroke categories.
3. **Hypertension vs Stroke** – Compares stroke records among individuals with and without hypertension.
4. **Feature Correlation Heatmap** – Displays correlations between numerical variables.
5. **Heart Disease vs Stroke** – Compares the proportion of stroke cases among individuals with and without heart disease.

An additional bar chart was used to visualize missing values.

## Key Findings

1. The dataset contains 5,110 records and 12 columns.
2. The BMI column contains 201 missing values, representing approximately 3.93% of the dataset.
3. Missing BMI values were handled using gender-wise median imputation.
4. The dataset contains 249 stroke cases and 4,861 non-stroke cases, indicating class imbalance.
5. The proportion of stroke cases is higher among individuals with heart disease (17.03%) compared to individuals without heart disease (4.18%).

## Conclusion

Exploratory Data Analysis helped understand the structure, quality, distributions, and relationships within the Stroke Prediction Dataset.

The visualizations provided useful insights into age, glucose levels, hypertension, heart disease, and stroke patterns.

This project demonstrates the use of Python and its data analysis libraries to explore and understand a real-world dataset.

## How to Run This Project

1. Clone or download this repository.
2. Make sure Python is installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the project folder.
5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Stroke_EDA.ipynb` and run the cells in order.



