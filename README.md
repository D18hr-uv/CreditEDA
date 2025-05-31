# CreditEDA
This is a ML-cum- Data Science project on the Credit EDA to describe the credit history of an individual.

This is the flow of code:
1) Importing the libraries pandas, numpy, matplotlib, seaborn, warnings, and the dataset application_data.csv.
2) Inspection of the data of the Application dataset.
3) Managing the columns with missing values:
     i. Greater than 47%    dropping
    ii. Greater than 31%   inputting the mean
   iii. Greater than 19%   imputing the mean
    iv. Greater than 13%   imputing the mean
     v. less than 1%       imputing the mode
4) Binning the year_birth Column and checking the Data Imbalance.
5) Dividing the Application Dataset with Target Variable as 0 and 1.
6) Performing Univariate, Bivariate, and multivariate analysis.
7) Co-relation between Numerical Columns by heatmap.
8) Further importing the Previous_application.csv.
9) Inspection of data of the Previous_application dataset.
10) Binning of continuous Variables.
11) Performing Univariate, Bivariate, and multivariate analysis.
12) Correlation between numerical Columns i.e., approved, refused, canceled, unused.

## DataSet
![image](https://github.com/user-attachments/assets/219cdef9-1c0b-4254-b58e-f41279827fdc)

## Dataset After cleaning
![image](https://github.com/user-attachments/assets/4e82da20-d216-4b65-932c-f19f59645383)

Since ots a numerical Colunms with no outliers and there is not much difference btw Mean and Median.Hence we can impute with mean or Median

## AMT_CREDIT_Category
![image](https://github.com/user-attachments/assets/92d9c371-155c-4057-8468-d82764a9b2d1)

## Binning YEARS_BIRTH Column
![image](https://github.com/user-attachments/assets/392d71b7-f746-4590-87b4-3a44d1b96f3e)

Most of the Applicants are between the age 25- 45 age group

## Pair Plot of Amount Columns for target 0
![image](https://github.com/user-attachments/assets/77e1880f-67bd-4ffa-8176-7f74db576be7)

## Confusion Matrix
![image](https://github.com/user-attachments/assets/a55d951f-a7e9-4760-a3d1-074b143e264b)

