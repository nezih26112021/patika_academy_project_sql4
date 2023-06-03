# patika_academy_project_sql4
query scenarios

Perform the following query scenarios on the "dvdrental" sample database.

1. Sort the different values in the "replacement cost" column in the movie table:

SELECT DISTINCT replacement_cost FROM film;

2. How many different data are there in the "replacement cost" column in the movie table?

SELECT COUNT (DISTINCT replacement_cost) FROM film;

3. How many of the movie titles in the movie table start with the character T and at the same time the rating is equal to 'G'?

SELECT COUNT (*) FROM film

WHERE title LIKE 'T%' AND  rating='G';

4. How many of the country names (country) in the country table consist of 5 characters?

SELECT COUNT (DISTINCT country) FROM country

WHERE country LIKE '_____';

5. How many of the city names in the city table end with the character 'R' or r?

SELECT COUNT (DISTINCT city) FROM city

WHERE city ILIKE '%r';
