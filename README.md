# 🏠London_House-DataAnalysis-using-Python_Pandas

**Project Overview**

This project focuses on performing data analysis and data cleaning using Python libraries like Pandas, Seaborn, and Matplotlib in Jupyter Notebook.

The dataset contains information related to areas, crime records, house prices, and dates. Various data preprocessing and analysis operations were performed to extract meaningful insights from the dataset.

**Technologies Used**

Python

Jupyter Notebook

Pandas

Seaborn

Matplotlib

**Libraries & Commands Used**

**Pandas Library-->import pandas as pd**

  Used to perform data manipulation and analysis.

**Reading CSV File-->pd.read_csv()**

  Used to import the CSV dataset into Jupyter Notebook.

**Counting Non-Null Values-->df.count()**

   Counts the number of non-null values in each column.

**Checking Missing Values-->df.isnull().sum()**

   Detects missing/null values from the dataframe.

**Seaborn Library-->import seaborn as sns**

   Used for data visualization.

**Matplotlib Library-->import matplotlib.pyplot as plt**

   Used for plotting graphs and charts.

**Heatmap for Missing Values-->sns.heatmap(df.isnull())**

   Displays missing values using a heatmap.

**Display Plot--.plt.show()**

   Used to display the graph.

**Checking Data Types-->df.dtypes**

   Shows datatype of each column.

**Convert Date Column to Datetime--.pd.to_datetime(df.Date)**

   Converts the Date column into datetime format.

**Extracting Year-->df.Date.dt.year**

   Creates a column containing only year values.

**Extracting Month-->df.Date.dt.month**

   Creates a column containing only month values.

**Insert New Column-->df.insert()**

   Used to insert a new column at a specific position.

**Drop Columns-->df.drop()**

   Removes columns permanently from dataframe.

**Grouping Data-->df.groupby()**

   Groups data based on unique column values.

**Filtering Records-->df[df.Column == 'Value']**

   Used to filter specific records.

**Group By with Mean-->df.groupby('Col_1')['Col_2'].mean()**

   Calculates mean values after grouping data.

**Tasks Performed**

**Q1. Convert Datatype of 'Date' Column**

Converted the Date column into Date-Time format using pd.to_datetime().

**Q2. Create 'Year' Column**

Added a new column named year containing only year values from the Date column.

**Q2(B). Create 'Month' Column**

Added a new column named month as the second column containing month values.

**Q3. Remove 'Year' and 'Month' Columns**

Deleted the columns year and month from the dataframe.

**Q4. Records Where No. of Crimes is 0**

Filtered all records where the number of crimes is zero and counted those records.

**Q5. Maximum & Minimum Average Price Per Year in England**

Used grouping functions to find maximum and minimum house prices per year in England.

**Q6. Maximum & Minimum Number of Crimes Per Area**

Calculated highest and lowest crime records for each area.

**Q7. Count of Records Where Average Price < 100000**

Displayed total count of records area-wise where average house price is less than 100000.

**Conclusion**

This project helped in understanding:

Data Cleaning
Handling Missing Values
Data Transformation
Grouping & Filtering Data
Data Visualization
Extracting Insights from Dataset

The project improved practical knowledge of Pandas operations and data analysis techniques used in real-world datasets.
