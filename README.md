Titanic Dataset – Exploratory Data Analysis (EDA)

Project Overview

    This project focuses on performing Exploratory Data Analysis (EDA) and data cleaning on the Titanic dataset using Python.    
    The main objective is to understand the dataset, analyze patterns related to passenger survival, handle missing values, and prepare the data for machine learning models.
    The project is implemented using VS Code with Jupyter Notebook.

Dataset Description

    Dataset Name: Titanic
    Source: Seaborn built-in dataset
    Number of records: 891 passengers
    Target variable: survived (0 = Not Survived, 1 = Survived)

Tools and Technologies Used

   -Python
   -Pandas
   -NumPy
   -Matplotlib
   -Seaborn
   -Jupyter Notebook
   -VS Code
   -Git and GitHub

Project Structure

    Titanic_EDA
    │
    ├── eda.ipynb
    ├── cleaned_titanic.csv
    ├── README.md

Exploratory Data Analysis (EDA)

The following EDA steps were performed:
    Dataset inspection using head(), info(), and describe()
    Checking data types and structure
    Missing value analysis
    Univariate analysis of important features
    Bivariate analysis between survival and features such as:
      -Gender
      -Passenger class
      -Age
      -Fare
    Correlation analysis
    Outlier detection using boxplots

Data Cleaning Process

    Filled missing values:
       Age was filled using the median
       Embarked was filled using the mode
    Dropped column with excessive missing values:
       Deck
    Removed duplicate rows
    Encoded categorical variables:
       Label encoding for binary features
       One-hot encoding for multi-class features
    Handled outliers in the Fare column using the IQR method

Key Insights

    Females had a higher survival rate than males.
    Passengers in 1st class survived more than 2nd and 3rd class.
    Younger passengers had a higher chance of survival.
    Fare and class are positively correlated with survival.



