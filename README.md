# Cabinet-Accessory-Company-Sales-Analysis


Suppose you are working as an assistent controller for a company, Cabinet Accessory Company (CAC), that sells cabinet hardware including knobs and pulls. Your direct superior gives you a dataset
with sales and cost data, covering the four-year period from 2014 to 2018, and asks you to perform a number of calculations based on this historical dataset.

NOTE: The dataset for this assignment is taken from the following website: https://accountingisanalytics.com.


Import the necessary libraries (pandas, NumPy, matplotlib and SciPy).
Import the 'Data' worksheet from the Excel-file ('dataset_cac.xlsx') and assign it to a DataFrame variable.
Rename the last three columns such that their column names do no longer contain spaces.
Convert the data type of 'customer_number' and 'date_of_sale' to string (object).
Check whether there are mistyped values (typos) in the 'region' column (in which there should be 8 unique values), and if so, replace them by the value that would result when the mistyped value
is fixed.
Calculate (and fill in) the values of the last three columns, and convert them to integers.
Select the data for "your" year (see the column "Year" of Table 1) and assign it to a variable.
Perform the calculations for "your" question set (see the column "Question set" of Table 1) based on the data for "your" year.
Create a new DataFrame that contains the total sales revenue, variable cost and contribution margin per region, and structure this DataFrame such that the regions are the columns (use the
transpose() method to achieve this).
Import the data from "your" two other worksheets (see the column "Other worksheets" of Table 1) from the Excel file and assign them to two DataFrame variables.
Calculate (and fill in) the values (which are sums) in the Segment Margin Report (i.e., the last DataFrame).



Provide a crosstabulation table showing the number of transactions per region per brand, and test whether the relationship between these two variables is significant using the chi-square test of
independence.
Calculate the average quantity sold per brand, and test whether the difference in average quantity sold between the two brands is significant using (a) the t-test for two independent samples and
(b) the Mann-Whitney test.
Provide a table showing the average sales revenue, variable cost and contribution margin per region per brand.
Provide a bar chart showing the average sales revenue, variable cost and contribution margin per region per brand.

Provide a crosstabulation table showing the number of transactions per region per brand, and test whether the relationship between these two variables is significant using the chi-square test of
independence.
Calculate the average quantity sold per region, and test whether the difference in average quantity sold between the eight regions is significant using (a) the one-way ANOVA test and (b) the
Kruskal-Wallis test.
Provide a table showing the average sales revenue, variable cost and contribution margin per region per brand.
Provide a bar chart showing the average sales revenue, variable cost and contribution margin per region per brand.
