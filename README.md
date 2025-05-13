# Task 1: Housing Data Cleaning

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : KUZIKKATIL ANAMIKA

*INTERN ID* : CT06WT245

*DOMAIN* : DATA SCIENCE

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

This project performs data cleaning and preprocessing on a housing dataset using pandas.

##  Key Steps

- Removed duplicates
- Cleaned the 'price' and 'status' columns
- Standardized binary values (yes/no)
- Saved cleaned data to 'cleaned_housing_data.xls'

## 📂 Files Included

- 'Housing.xlsx.xls' — Original dataset
- 'data_cleaning_task1.ipynb' — Jupyter Notebook with all steps
- 'cleaned_housing_data.xls' — Cleaned dataset

## Description

For this task, I worked with a housing dataset that required several preprocessing steps to make it suitable for analysis. The dataset included various property details such as price, availability of amenities, and status, but like most real-world datasets, it had issues that needed to be addressed before it could be used for modeling or visualization.

I started by removing duplicate entries using drop_duplicates() to ensure the dataset reflected unique observations. This is a crucial step for maintaining the integrity of any analysis or machine learning model.

Next, I cleaned the price column. The values included currency symbols and commas, which I removed using regular expressions. After that, I converted the cleaned strings into integers so they could be used in numerical computations.

The status column also had inconsistent formatting, including special characters like underscores and ellipses. I standardized this using regex to ensure the values were clean and uniform. Additionally, binary categorical columns like guestroom, airconditioning, and basement had values marked as 'y' and 'n'. I replaced these with more readable 'yes' and 'no' values.

After completing these cleaning steps, I saved the cleaned dataset as cleaned_housing_data.csv. The resulting dataset is free from duplicates, has properly formatted numerical and categorical values, and is ready for further analysis or machine learning applications.

## Output

![Image](https://github.com/user-attachments/assets/a39d31a3-cab8-4f0d-ae3e-0c284d8f1189)
