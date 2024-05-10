link to lesson

https://www.codecademy.com/courses/learn-sql-aggregate-functions/lessons/aggregate-functions/exercises/count

AGGREGATE FUNCTIONS
Count
3 min
The fastest way to calculate how many rows are in a table is to use the COUNT() function.

COUNT() is a function that takes the name of a column as an argument and counts the number of non-empty values in that column.

SELECT COUNT(*)
FROM table_name;

Here, we want to count every row, so we pass * as an argument inside the parenthesis.
