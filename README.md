#### Retail Orders ETL Data Project (Python + SQL)

> The project aims to execute an ETL (Extract, Transform, Load) data analytics process using Python and SQL focusing on analyzing the Retail Orders dataset, leveraging the Kaggle API for data extraction, Python (Pandas) for data cleaning and transformation, and SQL Server for data storage and querying.
> The final objective is to answer key business questions using SQL queries on the processed data.

![retail_orders_process](https://github.com/user-attachments/assets/2ae479a0-8183-40d2-bc9f-adf68b7ed4c9)

#### Steps:
> 1. **Data Extraction:** Use the Kaggle API to download the Retail Orders dataset with Python.
>    - Extract file from zip file
> 3. **Data Transformation:** Load the dataset into Pandas, clean and transform the data, and create new columns as needed.
>    - Change 'unknown' and 'Not Available' to NULL (nan)
>    - Rename column names, make them lower case, and replace space with underscore
>    - Derive new calculated columns: discount, sale price, and profit
>    - Convert order date from object data type to datetime
>    - Drop cost price, list price, and discount % columns
> 4. **Data Loading:** Load the cleaned data into SQL Server.
>    - Load the data into sql server using replace and append option
> 6. **Data Analysis:** Use SQL to answer business questions based on the cleaned data.
