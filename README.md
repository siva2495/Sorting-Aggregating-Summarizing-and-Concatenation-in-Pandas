# Sorting-Aggregating-Summarizing-and-Concatenation-in-Pandas

#### Sorting Data
We can sort the data by using sort_values( by = ‘ ‘)  function passing column name to by.

To sort the values in the descending order, we need to set parameter ascending = False.

In the by parameter pass the list of columns on which we want to sort and for the ascending parameter pass the boolean list True for ascending and False for descending.

#### Aggregating and Summarizing DataFrame 
Here we will see

•	How to calculate sum, mean, median and mode of a column

•	How to get the summary of the numerical variables

•	How to get number of missing values in each columns

•	How to group the data based on categories of one column

•	How to group the data based on categories of multiple columns

•	How to create new feature using the aggregated results of a column

#### CROSS TAB
The crosstab() function is used to compute a frequency table of two or more factors.

By default, it computes a frequency table of the factors unless an array of values or an aggregation function which is passed.

Learn more about crosstab here: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.crosstab.html

#### We can group the data by using the pivot table also
Learn more about the pivot table here:

https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html

https://www.analyticsvidhya.com/blog/2020/03/pivot-table-pandas-python/


#### Working with Multiple DataFrames 
•	In most of the real life projects you will not get data from a single resource. You might need to combine data that you gather from multiple sources. In this notebook, we will see how to work with multiple data files

#### CONCATENATE ALL THE DATAFRAMES
We will use the concat function to concatenate all the dataframes. You just need to pass the list of dataframes to concatenate.
FOR ROW-WISE CONCATENATION USE AXIS=0

#### FOR COLUMN-WISE CONCATENATION USE AXIS=1
It is not advised to concatenate dataframes column wise. If you want to then you need to take care of some checks like the number of rows must be same in both the dataframes. Indexes are sorted of both the dataframes. If you are done with all the checks then you can simply use axis=1 to do the job.

