link to lesson:
https://www.codecademy.com/courses/learn-sql-aggregate-functions/lessons/aggregate-functions/exercises/sum


AGGREGATE FUNCTIONS
Sum
1 min
SQL makes it easy to add all values in a particular column using SUM().

SUM() is a function that takes the name of a column as an argument and returns the sum of all the values in that column.

What is the total number of downloads for all of the apps combined?
```
SELECT SUM(downloads)
FROM fake_apps;
```
This adds all values in the downloads column.
