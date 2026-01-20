# Titanic Dataset – Exploratory Data Analysis (EDA)

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** and **data cleaning** on the **Titanic dataset** using **Python**.  
The goal is to understand the dataset, discover patterns related to passenger survival, handle missing values, and prepare the data for machine learning models.

The project is implemented using **VS Code with Jupyter Notebook**.

---

## Dataset Description
- **Dataset Name:** Titanic
- **Source:** Seaborn built-in dataset
- **Number of Records:** 891 passengers
- **Target Variable:** `survived`  
  - 0 → Not Survived  
  - 1 → Survived

---

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git and GitHub

---


---

## Exploratory Data Analysis (EDA)
The following EDA steps were performed:

- Dataset inspection using `head()`, `info()`, and `describe()`
- Understanding data types and dataset structure
- Missing value analysis
- Univariate analysis of important features
- Bivariate analysis between survival and:
  - Gender
  - Passenger class
  - Age
  - Fare
  - Embarked port
- Correlation analysis
- Outlier detection using boxplots

---

## Data Cleaning Process
- Handled missing values:
  - Filled `age` using median value
  - Filled `embarked` using mode value
- Dropped column with high missing values:
  - `deck`
- Removed duplicate records
- Encoded categorical variables:
  - Label encoding for binary features
  - One-hot encoding for multi-class features
- Handled outliers in the `fare` column using the IQR method
- Saved the cleaned dataset as `cleaned_titanic.csv`

---

## Key Insights
- Females had a higher survival rate than males.
- Passengers in 1st class survived more than 2nd and 3rd class.
- Younger passengers had a higher chance of survival.
- Fare and class are positively correlated with survival.
---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Open the project folder in VS Code

3. Install the required libraries
    command: python -m pip install pandas numpy matplotlib seaborn jupyter

4. Open the file

    file: eda.ipynb

5. Select the Python kernel

6. Run all notebook cells sequentially

