## Business tasks
Initially we performed data cleaning on the dataset, dropping irrelevant columns and generated useful business insights. Given below are the step by step analysis that has been performed in Employee_payroll data.

1. Remove the **'$'** and **‘,’** signs from the **'Base Pay'** column and change the column's data type to float (Use pandas for this and not excel)

2. Create a column **'Fiscal Year'** in which you will get the **'Fiscal Year'** from the **'Fiscal Period'** column.

3. Remove the columns **‘Middle Init’, ’Office’, ’Job Code’, and ‘Position ID’ from the DataFrame.**

4. Get the count of unique values for the columns **'Fiscal Year'**, **' Office Name'**, **'Job Title'**, and **'Bureau'**

7. How many Job Titles contain **'Service'** in it?

8. Print the Highest **'Base Pay'** of every **'Office Name'**.

9. Create a Dataframe having **'Original Hire Date'** as its index and  **'Job Title'** and **'Base pay'** are columns

10. Find the average **'Base pay'** of every **'Fiscal Year’**.

11 Create 3 DataFrames **'df_2016'**, **'df_2017',** and **'df_2018'** where each dataframe will contain data only from those **'Fiscal Year’**.

12. Get all the details where **'Job Title'** is **'Operating Engineer II'** and the **'Base Pay'** is less than 29000 and greater than 25000

13. Concat the above 3 Dataframes created  **'df_2016'**, **'df_2017',** and **'df_2018'**, to create a new DataFrame.

14. Get all the details of Employees whose **'Base Pay'** is the minimum or **'Base Pay'** is the maximum

1. For each ‘**Office Name**’ and ‘**Job Title’**  find the first and second highest  **'Base Pay'**  salary.
