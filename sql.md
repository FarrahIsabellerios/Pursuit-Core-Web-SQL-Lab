Find Movie:
SELECT title FROM movies;

SELECT director FROM movies;

SELECT *
FROM movies
WHERE year NOT BETWEEN 2000 AND 2010


SELECT *
FROM movies
WHERE Id BETWEEN 1 AND 5



SELECT *
FROM movies
WHERE NOT Director LIKE 'John%'


syntax SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC;

SELECT DISTINCT Director FROM Movies 
ORDER BY Director ASC

SELECT * 
FROM Movies 
ORDER BY Title ASC
LIMIT 5

SELECT title FROM movies
ORDER BY title ASC
LIMIT 5 OFFSET 5;