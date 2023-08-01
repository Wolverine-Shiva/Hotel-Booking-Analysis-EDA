# Hotel-Booking-Analysis-EDA
The Hotel Booking Analysis project aimed to perform Exploratory Data Analysis (EDA) on a dataset with Hotel Booking Information, comprising two hotel descriptions: City Hotel and Resort Hotel.
The dataset contains 119,390 rows and 32 columns.

The data manipulation workflow is divided into three categories:
1. Data Collection,
2. Data Cleaning and Manipulation,
3. EDA (Exploratory Data Analysis).

Initially, data was collected using methods like Head(), tail(), info(), describe(), and columns().
Unique values of each column were tabulated, and incorrect data types were corrected during Data Cleaning. Duplicate data items (87396) were removed.
Next, Data Wrangling was done by checking for 'null values' and dropping columns with many nulls, such as the "company" column. For columns with minimal nulls, the null values were filled with necessary data using .fillna().
Data visualization was accomplished using different charts to gain better insights and achieve Business objectives.
