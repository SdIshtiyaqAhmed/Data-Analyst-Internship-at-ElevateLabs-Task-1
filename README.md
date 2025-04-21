# Data Analyst Internship at ElevateLabs - Task 1

Downloaded the sales_data.csv from Kaggle [https://www.kaggle.com/datasets/imranlukman/amazon-online-sales-dataset]

Then the process of Data cleaning was performed using pandas module in python programming language as follows:

1. The sales_data.csv file was imported into the python program by using read_csv() function from pandas module
2. The Null values were removed from the dataset using dropna() function
3. The Duplicate values were removed from the dataset using drop_duplicates() function
4. Then the index of the dataset was reset using reset_index() function
5. The following coloumns were iterated over:
    i. Row ID - changed the values of this coloumns to adapt to the new dataset with deleted rows.
    ii. Order Date & Ship Date - made all the values of these coloumns consistent.
6. Changed the data types of coloumns to match the datatype of the values in those coloumns
7. Renamed the coloumns of the dataset by removing spaces and making the coloumn names lower case
8. Exported or Saved the resultant dataset as a file named as cleaned_sales_data.csv
