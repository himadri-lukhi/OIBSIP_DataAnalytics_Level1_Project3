# OIBSIP_DataAnalytics_Level1_Project3
# NYC Airbnb Data Cleaning Project

## Project Overview

This project focuses on cleaning and preprocessing the NYC Airbnb dataset using Python and Pandas. The objective was to improve data quality by handling missing values, validating records, identifying outliers, and preparing the dataset for further analysis.

## Objectives

* Identify and handle missing values.
* Check for duplicate records.
* Verify data types and dataset consistency.
* Detect and analyze outliers.
* Remove invalid records.
* Prepare the dataset for further analysis and visualization.


## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab


## Dataset Information

* Dataset: NYC Airbnb Open Data
* Total Records: 48,895
* Total Features: 16
* File Format: CSV

---

## Data Cleaning Process

### 1. Data Exploration

* Loaded the dataset into Google Colab.
* Examined dataset structure, dimensions, and data types.
* Generated descriptive statistics.

### 2. Missing Value Handling

* Filled missing values in the `name` column with "Unknown Listing".
* Filled missing values in the `host_name` column with "Unknown Host".
* Replaced missing values in `reviews_per_month` with 0.
* Retained missing values in `last_review` because they indicate listings that have not received any reviews.

### 3. Duplicate Check

* Checked for duplicate records.
* No duplicate records were found in the dataset.

### 4. Data Validation

* Verified column data types and dataset consistency.
* Confirmed that categorical and numerical columns were properly formatted.

### 5. Outlier Analysis

* Created boxplots for the `price` and `minimum_nights` columns.
* Identified extreme values using visual analysis.
* Removed listings with invalid price values (`price = 0`).
* Retained valid extreme values because they may represent luxury accommodations or long-term rental policies.



## Conclusion

The NYC Airbnb dataset was successfully cleaned and validated by handling missing values, checking for duplicate records, removing invalid entries, and analyzing outliers. The cleaned dataset is now more accurate, consistent, and reliable for further analysis, visualization, and machine learning applications.


