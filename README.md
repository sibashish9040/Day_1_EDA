# Day_1_EDA
## Titanic Dataset - Exploratory Data Analysis (EDA)
This project focuses on Exploratory Data Analysis (EDA) of the Titanic dataset. The goal was to explore and clean the dataset, handle missing values, and perform basic data analysis.

### 1. What I Did
1. Data Loading: Loaded the Titanic dataset for analysis.

2.  Missing Data Handling: Identified and handled missing values:

    * Filled missing `Age` values with the median (both overall and grouped by `Pclass`).

    * Dropped the `Cabin` column due to too many missing values.

3. Feature Engineering: Extracted the `Title` from the `Name` column to create a new feature.

4.  Data Cleaning: Cleaned the data for better analysis, including transforming features where necessary.

### Libraries Used
* Pandas
* NumPy

