link to lesson:

https://www.codecademy.com/courses/learn-sql-aggregate-functions/lessons/aggregate-functions/exercises/round


AGGREGATE FUNCTIONS
Round
5 min
By default, SQL tries to be as precise as possible without rounding. We can make the result table easier to read using the ROUND() function.

ROUND() function takes two arguments inside the parenthesis:

a column name
an integer
It rounds the values in the column to the number of decimal places specified by the integer.
```
SELECT ROUND(price, 0)
FROM fake_apps;
```
Here, we pass the column price and integer 0 as arguments. SQL rounds the values in the column to 0 decimal places in the output.


