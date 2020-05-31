# data-612

Assignment 2 README

First, I imported the HomeGames.csv file instead of the AllstarFull.csv file as I did in my first assignment because it had dates instead of years for date data.

1. I found the maximum date of my data by using the max function to locate the latest date in the span.last column.
2. I converted the span.last column to YYYY-MM-DD format and subtracted the dates from the maximum date in the converted span.last column.
3. I imported numpy and converted the new "subdates" column from a count of days to a count of months.
4. Throughout the assignment, I had already created and saved the new column with this updated different in months.
5. I saved the updated dataframe as a csv file.
