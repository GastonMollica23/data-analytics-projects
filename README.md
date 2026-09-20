# data-analytics-projects
The purpose of these projects is to practise cleaning data. 

Sheet 1 has the original data set, Sheet 2 has the dataset after the cleaning process. 

Monthly Sales data -

This project's only purpose was to take a dataset and create a visual table to represent the data in an easy to read way

In order to accomplish this, select cell A1> Insert> Chart> Customize

From here, you can change different aspects of the chart. 

Cleaning with Spreadsheets -

This project taught me how to clean data using different techniques, such as:

Data Cleaning: Applied filters to identify inconsistencies and remove unnecessary or incorrect data.

Data Organisation: Used spreadsheet tools to restructure and organise the dataset for analysis.

Data Preparation: Reviewed and refined the dataset to ensure it was clean, consistent, and ready for analysis.

Tasks

1. Remove blank cells. 
Create Filter then filter using the condition "is empty". Do this for every column

2. Transposing. Creating more columns than rows
Copy the data, paste it in another column by right clicking and selecting transpose

3. Get rid of the exrta spacing
HIghlight the data> Data Clean Up> Trim White Spaces

5. Delete all new formatting
Highlight the data> Format> Clear Formatting

Boba Tea Shop

Another cleaning exercise using Google Sheet functions

1. Remove duplicates	
Data> Data Cleanup> Remove duplicates. Select the id and company name, remove duplicates 

2. Correct the ratings	

The COUNTIF funtion counts the given range and returns a count of rows that meets the criteria. =COUNTIF(C:C,">5") needs to go into a new column. 
    The first entry (C:C) refers to the range where you are counting the data. In this case, the range is the entire rating column (C), which contains the Yelp ratings. The second entry refers to the criterion (>5), and tells the function to count all the values greater than 5. 
    This should return a value of 9, meaning that 9 values are greater than 9 and incorrect. Any one of these values will be replaced with a 5
    Finding these 9 rating above 5. Highlight the data> Sort Range> Advanced> Has header then sort from Z-A using rating

3. Splitting the latitude and longitude columns in 2	

Use this split funtion to create 2 new columns. Once this is done, replace the original 1 column with the 2 newly created ones

4. Adding a negative value to the longitude column values

Paste =G2*-1 in an empty column then paste the new values where they need to go