# Assignment-2-Data-cleaning-and-Transformation
This assignment focuses on cleaning and transforming a product dataset using Microsoft Excel.The objective is to improve data quality ,maintain consistency, identify missing values, and prepare the dataset for further analysis.
first task is Handling Missing Values
identified 3 missing values in the price column and used the COUNTBLANK() function to count missing values.calculated the median price using the MEDIAN() function.The calculated median was $130.Replaced the 3 missing price values with the median value of $130
Identified 4 missing values in the category column.checked the product name and brand name to determine the appropriate categories.planned to assign suitable categories based on product information.
correcting inconsistent data
standardised product names using the PROPER() and TRIM() functions.removed unnecessary spaces.corrected inconsistent capitalisation.standardized category names.corrected the spelling inconsistency from "Electroni" to "Electronics".
Removing Duplicates
selected the complete dataset.used the data tabs remove duplicate feature.selected all columns to identify duplicate rows based on the entire row.removed duplicate records .
3 duplicate values found and removed.
splitting and merging data
used text to columns to split product ID .Separated the manufacturing date information and country code.used flash fill to combine the day and month information.
Merging Brand name and product name
created a new column named product brand.combined brand name and product name using flash fill.
Number formatting
Formatted the price column as currency.converted manufacturing date values to dates using the year 2026.applied the required date format:DD-MM-YYYY.
Conditional Formatting.
Applied data bars to the price column to visually compare product prices.
created a conditional formatting rule to highlight products belonging to the electronics category.
This assignment helped me improve my practical Excel skills and understand the importance of data cleaning and transformation in Data Analytics.
