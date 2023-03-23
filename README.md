# DATA-CLEANING-CHALLENGE-WITH-SQL-FIFA-21-dataset
![fifa](https://user-images.githubusercontent.com/100960483/227168430-f7cd47b8-e5e4-49d7-a56f-d1b2b745e593.PNG)

https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring

[Uploading fifa21 raw data v2.xlsx…]()

1. INTRODUCTION

I was excited to participate in the #DataCleaningChallenge organized by Promise Chinonso. Data cleaning is the heart and soul of Exploratory data analysis (EDA). It is estimated that data cleaning process alone takes up 60% of the data analysis process. Data Cleaning ensures that relevant, correct, consistent and complete dataset is employed in analysis. I made use of SSMS (SQL SERVER MANAGEMENT STUDIO) and a lit bit of excel (prior to uploading the data in SSMS) to clean the dataset.

2. What to consider when cleaning your data

Incorrect data types

Null entries

Duplicate rows/columns

Misspelling

Missing values

Irrelevant data

Special Characters

3. Observations from our previewed data

Number of rows = 18979

Number of columns = 77

SM, IR and W/F columns has special characters which has to be removed.

Height  are not consistent, in the height column, some rows are represented in cm while some are represented in feet/inches. 

The value, Wage and Release clause columns are represented in M and K which are the million and the thousand sign respectively and as well as special characters

The loan date end column has numerous amount of null values.

The club columns have some rows with unwanted characters

Misspelling in the LongName column
