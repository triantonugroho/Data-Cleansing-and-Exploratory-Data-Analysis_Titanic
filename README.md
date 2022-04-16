# Data Cleansing
Data cleaning means:
- correcting/addressing any mistakes in the data
- organising the data in ways to help the downstream analysis e.g., clearer variable names, factor levels, data transformation

Execution in cleaning data is simply divided into two, namely data imputation and data amputation.
## Data amputation
Data amputation is performed if the data condition shows too many empty data (null) or too many unique data and other considerations.
## Data imputation
There are several ways in imputing data.
 - Data imputation with mean can be done for data that is normally distributed
 - Data imputation with median can be done for skewness data
 - Data imputation with mode can be performed for categorical data

# Exploratory Data Analysis
Exploratory Data Analysis, or EDA, is an important step in any Data Analysis or Data Science project. EDA is the process of investigating the dataset to discover patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset. EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better.
## Importing Libraries
Importing the required libraries for Exploratory Data Analysis (pandas, numpy, matplotlib, and seaborn)
## Uploading Data Set
Uploading the Titanic.csv from existing location to the google colab
## Reading Data Set
Read the Titanic.csv dataset
## Changing Index
- Pandas default index starts from 0
- While the dataset index of the PassengerId column starts from 1
- Then we will use the index dataset of column PassengerId
## Displaying DataFrame Information
The info() method prints information about the DataFrame. The information contains the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values). Note: the info() method actually prints the info.
## Checking Missing Value
Checking whether there is a missing value (NaN) and also counting the number of the missing value in each columns in the dataset.
## Removing Duplicate Data
Remove all of duplicate data from the dataset.
