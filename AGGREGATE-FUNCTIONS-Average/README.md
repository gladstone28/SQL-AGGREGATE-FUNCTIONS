link to lesson:

https://www.codecademy.com/courses/learn-sql-aggregate-functions/lessons/aggregate-functions/exercises/avg


AGGREGATE FUNCTIONS
Average
2 min
SQL uses the AVG() function to quickly calculate the average value of a particular column.

The statement below returns the average number of downloads for an app in our database:
```
SELECT AVG(downloads)
FROM fake_apps;
```
The AVG() function works by taking a column name as an argument and returns the average value for that column.
