# Database-Processing-M7<br>
### Part 1<br>

a.	Write a function to generate a list of x random numbers, where x is the parameter indicating how many numbers to generate and each number falls in the range between 21 and 100.<br> 

b.	Use your function to create a list of 50 random numbers with your code and use pandas.Series to determine how many of the numbers are below 33<br>

c.	Using the same list of 50 random numbers, 1) create a numpy array, modify it to 5x10 (you can do this by calling numpy.reshape(yourArray, (5,10)) and then replace all the numbers that are greater than or equal to 50 (50-100) by 50.<br>
<br>
### Part 2<br>
a.	Create a new SQL table for the user dictionary. It should contain the following attributes “id”, “name”, “screen_name”, “description” and “friends_count”. Modify your SQL table from Module 5 to include “user_id” columns which will be a foreign key referencing the user table.<br>
<br>b.	Write python code that is going to read and load the Assignment5.txt file directly from the web and populate both of your tables (Tweet table from Module5 and User table from this assignment). You can use the same code from the previous assignment with an additional step of inserting data into the newly created table.
For tweets that could not parse, write them into a Module7_errors.txt file.<br>
<br>
### Part 3<br>

a.	Write a PL/SQL trigger that will cap the course number column in the university.sql database at 598. That is, any time an update or an insert would provide course number 599 or higher, automatically reset the value back to 598. Be sure to verify that your trigger is working with some sample data.
<br>
b.	Write a regular expression to match credit card numbers, assuming a 16-digit credit card that may or may not include spaces after each 4 digits. Create the code to validate that your regular expression works in either python or Oracle.

