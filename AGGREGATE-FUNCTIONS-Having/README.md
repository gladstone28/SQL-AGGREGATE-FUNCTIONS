link to lesson:
https://www.codecademy.com/courses/learn-sql-aggregate-functions/lessons/aggregate-functions/exercises/having


AGGREGATE FUNCTIONS
Having
7 min
In addition to being able to group data using GROUP BY, SQL also allows you to filter which groups to include and which to exclude.

For instance, imagine that we want to see how many movies of different genres were produced each year, but we only care about years and genres with at least 10 movies.

We can’t use WHERE here because we don’t want to filter the rows; we want to filter groups.

This is where HAVING comes in.

HAVING is very similar to WHERE. In fact, all types of WHERE clauses you learned about thus far can be used with HAVING.

We can use the following for the problem:

SELECT year,
   genre,
   COUNT(name)
FROM movies
GROUP BY 1, 2
HAVING COUNT(name) > 10;

When we want to limit the results of a query based on values of the individual rows, use WHERE.
When we want to limit the results of a query based on an aggregate property, use HAVING.
HAVING statement always comes after GROUP BY, but before ORDER BY and LIMIT.
