DATA ANALYSIS USING NUMPY AND PANDAS

Introduction

This assignment focuses on the basics of data analysis using Python libraries such as NumPy and Pandas. Through these exercises, I practised creating, exploring, and manipulating different types of datasets.
I started by working with NumPy arrays to perform temperature conversions, mathematical calculations, indexing, and slicing. I then explored Pandas Series and DataFrames using student marks and transaction datasets.
I also practised important data analysis operations such as filtering records, accessing specific values, updating existing data, grouping information, and adding or removing rows and columns.
This assignment helped me gain a better understanding of how NumPy and Pandas are used for basic data handling and analysis in Python.

Objectives

To understand how to create and work with one-dimensional and two-dimensional NumPy arrays.
To explore array properties such as shape, size, dimensions, and data types.
To perform mathematical calculations and temperature conversions.
To understand indexing and slicing techniques.
To create and manipulate Pandas Series using custom index labels.
To retrieve, update, filter, and delete Series values.
To calculate CGPA values from student marks.
To create and explore Pandas DataFrames.
To select and filter records based on specific conditions.
To identify unique values and count records.
To perform grouping and calculate average values.
To add, update, and remove rows and columns from a DataFrame.

NumPy Array Operations

One-Dimensional Array

Created a NumPy array named `temperatures_w1` to store daily temperature readings for Week 1.
Explored array properties such as shape, data type, and size.
Converted Celsius temperatures into Fahrenheit.
Practised indexing and slicing to retrieve specific temperature values.

Two-Dimensional Array

Created a two-dimensional NumPy array named `temperatures` to store temperature readings for two weeks.
Checked the array's dimensions, shape, and other properties.
Accessed individual week records using indexing and slicing.

Pandas Series Operations

Created a NumPy array containing student marks.
Prepared custom index labels from Rank1 to Rank5.
Converted the data into a Pandas Series.
Used `iloc` to access values based on their positions.
Used `loc` to retrieve values using index labels.
Updated the mark associated with Rank1.
Removed the Rank5 entry.
Calculated CGPA by dividing student marks by 10.

Pandas DataFrame Operations

DataFrame Creation

Created a DataFrame named `transactions` using transaction details.
Included columns such as Transaction ID, Product Category, Region, and Amount.
Entered and displayed the transaction records.

Data Exploration and Analysis

Used `head()` and `tail()` to view records.
Checked the DataFrame structure using `shape`, `columns`, and `dtypes`.
Selected specific columns using column selection.
Retrieved columns using `iloc`.
Filtered transactions based on Region and Amount conditions.
Used `value_counts()` to count transactions in each product category.
Used `unique()` to identify different regions.
Applied `groupby()` to calculate the average transaction amount for each region.

Data Manipulation

Updated the Amount for Transaction ID 102 using `loc`.
Created a new Discount column by calculating 10% of the transaction amount.
Removed the record with Transaction ID 109.
Deleted the Discount column using the `drop()` method.

Learning Outcomes

By completing this assignment, I gained practical knowledge of using NumPy and Pandas for basic data analysis.
I learned how to create and work with arrays, Series, and DataFrames. I also gained experience in retrieving specific records, applying conditions, performing calculations, grouping data, and modifying datasets.
These exercises helped me improve my understanding of Python data analysis libraries and build a foundation for working with real-world datasets.

Conclusion

Overall, this assignment was a useful learning experience that helped me understand the fundamental concepts of data analysis using NumPy and Pandas.

Through hands-on practice, I became more familiar with handling datasets, performing calculations, exploring data, and manipulating records using Python.

This practical knowledge will be helpful as I continue learning more advanced data analysis concepts and working on future projects.
