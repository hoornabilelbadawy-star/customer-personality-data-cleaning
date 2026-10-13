
Customer Personality Analysis – Data Cleaning

Project Overview

This project focuses on cleaning and preparing the Customer Personality Analysis dataset using Excel Power Query as part of my internship with Swynex.

The goal is to improve data quality and prepare the dataset for further analysis.

Dataset

The dataset contains customer information, including income, education, marital status, enrollment dates, and responses to marketing campaigns.

Source: Customer Personality Analysis – Kaggle

Tools Used

* Microsoft Excel
* Power Query

Data Cleaning Steps

1. Checked the ID column for duplicate values.
2. Trimmed unnecessary spaces in the Education and Marital_Status columns.
3. Identified unexpected marital status values, such as Absurd and YOLO, for further review.
4. Investigated missing Income values and created an Income_Cleaned column, filling missing values with the median while preserving the original column.
5. Converted the enrollment date column from text to date format using the appropriate locale.
6. Reviewed potential income outliers.
7. Converted campaign acceptance, complaint, and response indicators from numeric values into readable labels.
8. Reviewed constant-value columns for their relevance to future analysis.

Notes

Cleaning decisions were made to improve consistency while preserving the original data where appropriate. Unexpected values and potential outliers were flagged for review rather than automatically removed.

Current Status

Data cleaning and preparation are in progress. Further analysis may follow after the data quality checks are completed.
