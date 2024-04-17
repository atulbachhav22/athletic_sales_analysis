# athletic_sales_analysis

#Combine and Clean the Data

Import the two CSV files, athletic_sales_2020.csv and athletic_sales_2021.csv, and read them into DataFrames.

Check that the columns in the two DataFrames have similar names and data types.

Combine the two DataFrames by the rows using an inner join, and reset the index.

After combining the DataFrames, do the following:

    Check if there are any null values.

    Check each column’s data type.

    Convert the "invoice_date" column to a datetime data type.

    Confirm that the data type has been changed.


#Determine which Region Sold the Most Products

Use either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.

Rename the aggregated column to reflect the aggregation of the data in the column.

Sort the results in descending order to show the top five regions, including the state and city that have the greatest number of products sold. Your final table should look like the following image:

#Determine which Region had the Most Sales
Use either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.

Rename the aggregated column to reflect the aggregation of the data in the column.

Sort the results in descending order to show the top five regions, including the state and city that generated the most sales. Your final table should look like the following image:

#Determine which Retailer had the Most Sales
Use either the groupby or pivot_table function to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns.

Rename the aggregated column to reflect the aggregation of the data in the column.

Sort the results in descending order to show the top five retailers along with their region, state, and city that generated the most sales. Your final table should look like the following image: