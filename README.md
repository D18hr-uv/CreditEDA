# CreditEDA
This is a ML-cum- Data Science project to on the Credit EDA to describe the credit history of an individual.

This is the flow of code:
1) Importing the libraries pandas, numpy, matplotlib, seaborn, warniing and the dataset application_data.csv.
2) Inspection of data of the Application dataset.
3) Managing the columns with missing values:
     i. Greater than 47%    dropping
    ii. Greater than 31%   imputing the mean
   iii. Greater than 19%   imputing the mean
    iv. Greater than 13%   imputing the mean
     v. less than 1%       imputing the mode
4) Binning year_birth Column and checking the Data Imbalance.
5) Dividing the Application Dataset with Target Variable as 0 and 1.
6) Performing Univariate, Bivariate, and multivariate analysis.
7) Co-relation between Numerical Columns by heatmap.
8) Further importing the Previous_application.csv.
9) Inspection of data of the Previous_application dataset.
10) Binning of continuous Variables.
11) Performing Univariate, Bivariate, and multivariate analysis.
12) Co-relation between numerical Columns i.e. approved, refused, canceled, unused.
