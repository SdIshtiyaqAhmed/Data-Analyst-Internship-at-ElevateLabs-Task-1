# Data Analyst Internship at ElevateLabs - Task 1

Downloaded the sales_data.csv from Kaggle [https://www.kaggle.com/datasets/imranlukman/amazon-online-sales-dataset] then the process of Data cleaning was performed using the pandas module in the Python programming language as follows:

1. The sales_data.csv file was imported into the python program by using read_csv() function from pandas module
2. The Null values were removed from the dataset using the dropna() function
3. The Duplicate values were removed from the dataset using the drop_duplicates() function
4. Then the index of the dataset was reset using the reset_index() function
5. The following columns were iterated over:
    - Row ID - changed the values of this column to adapt to the new dataset with deleted rows.
    -  Order Date & Ship Date - made all the values of these columns consistent.
6. Changed the data types of columns to match the datatype of the values in those columns
7. Renamed the columns of the dataset by removing spaces and making the column names lowercase
8. Exported or saved the resultant dataset as a file named cleaned_sales_data.csv
