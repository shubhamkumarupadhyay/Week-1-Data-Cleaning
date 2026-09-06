# Week 1 - Data Acquisition, Cleaning and Preprocessing

## Project Overview

This project was completed as part of my internship task on data acquisition, data cleaning, and preprocessing. The Titanic passenger dataset was selected as a real-world dataset for practicing different data preparation techniques.

## Objective

The main objective of this project was to understand a real-world dataset, identify data quality issues, clean the data, and prepare it for further analysis and machine learning applications.

## Dataset

The Titanic dataset contains information about passengers, including:

- Passenger class
- Age
- Sex
- Number of siblings/spouses
- Number of parents/children
- Fare
- Cabin information
- Port of embarkation
- Survival status

The original dataset contained 891 rows and 12 columns.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Microsoft Word

## Data Cleaning

The following data cleaning activities were performed:

- Identified missing values
- Handled missing Age values using median imputation
- Handled missing Embarked values using the mode
- Created a CabinAvailable feature
- Checked for duplicate records
- Checked categorical values for inconsistencies
- Investigated potential outliers

## Data Preprocessing

Categorical variables were converted into numerical form using one-hot encoding. The Sex and Embarked variables were encoded to make the dataset more suitable for further analysis and machine learning.

## Outlier Analysis

Potential outliers in the Fare variable were identified using the Interquartile Range (IQR) method. A total of 116 potential Fare outliers were identified. These values were retained because they may represent genuine passenger fares.

## Results

The project improved my understanding of the complete data preparation process, including data exploration, missing-value treatment, duplicate checking, outlier analysis, and categorical encoding.

## Files Included

- `Week_1_Data_Cleaning.ipynb` - Python notebook containing the analysis and preprocessing work
- `titanic_cleaned.csv` - Cleaned dataset
- `Week_1_Internship_Report.docx` - Detailed project report
- `README.md` - Project documentation

## Conclusion

This project provided practical experience in preparing real-world data for further analysis. It helped me understand how appropriate data cleaning and preprocessing techniques can improve data quality and usability.
