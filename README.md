# data-612

Assignment 6 README

I had quite a bit of trouble grasping the concepts in this week's assignment. I used the Parks.csv and Salaries.csv files for this assignment.

1. I imported the Parks.csv dataset and checked the variable types.
2. I made sure the 'park.alias' variable was set to "str".
3. I searched for and returned values from the 'park.alias' column up to the first semicolon and created a new column named 'park.alias_cleaned' that included this new information using regular expressions.
4. I imported the Salary.csv file and checked the variable types.
5. I created an equation that would return mean, sum, median, mode, and range for column 5 (Salary) from the Salary.csv dataset.
6. I attempted to apply the created equation to the Salaries dataset just like an example in the Lecture 6.2 notes, but was unable to achieve success in application.

Assignment 5 README

For this assignment, I used the HallofFame.csv file.

1. I imported the dataset and checked the original "dtypes". This showed me the current types of all variables in the dataset.
2. I converted the veriable "category" to a categorial variable, since it was previously a string variable (object).
3. I converted the variable "yearID" to a string variable, since it was previously an integer.

Assignment 4 README

For this assignment, I merged the AllstarFull.csv and AwardsPlayers.csv files. 

1. I used the concat function to inner join these two files. 
2. I counted the number of null values in each row.
3. I noticed that there were more than a thousand null values in the startingPos, tie, and notes columns. I then dropped these columns since, if I were to use this data for analysis, I would likely not use those columns.
4. I then recounted the number of null values in each of the remaining rows. With over 5000 rows remaining and only around 50 rows with null values, I decided to drop these rows as the data would still hold its integrity.
5. At this point, no more null values remained.


Assignment 3 README

I imported the AwardsPlayers.csv file for this assignment.

1. I created a distplot to view the density for the yearID variable. It displayed a desity count of awards for each year.
2. I created a countplot to view the number of awards won per league. 
3. Finally, I created a violinplot to compare each league's awards over time. It was not a very nice-looking plot. I imagine I would have to know more about how to manipulate the sizes for these plots to be able to disply the data in a friendlier format. 

Assignment 2 README

First, I imported the HomeGames.csv file instead of the AllstarFull.csv file as I did in my first assignment because it had dates instead of years for date data.

1. I found the maximum date of my data by using the max function to locate the latest date in the span.last column.
2. I converted the span.last column to YYYY-MM-DD format and subtracted the dates from the maximum date in the converted span.last column.
3. I imported numpy and converted the new "subdates" column from a count of days to a count of months.
4. Throughout the assignment, I had already created and saved the new column with this updated different in months.
5. I saved the updated dataframe as a csv file.
