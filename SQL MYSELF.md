# SQL
## Where conditions
> 1. SELECT * FROM movies where id= 6
> 2. SELECT * FROM movies where id Between 1 and 5 
> 3. SELECT * FROM movies where id not Between 1 and 5 
> 4. SELECT Title, Year FROM movies where id in (1,2,3,4,5)
***
## Like 
>   1. SELECT * FROM movies where Title like "%Toy Story%"
>   2. SELECT * FROM movies where Director not like "%John Lasseter%";
>  3. SELECT City, Population FROM north_american_cities where country like "%Ca%";
***
## DISTINCT
> SELECT DISTINCT Director FROM movies
***
## Order by and offset/ limit
> 1. SELECT Director FROM movies order by Director asc
> 2. select title , year from movies order by year desc limit 4
> 3. select * from movies order by title asc limit 5
> 4. select * from movies order by title asc limit 5 offset 5
## where -like -order by -limt - offset
> 1. select city from North_american_cities where country like "%Mexico%" order by population desc limit 2
> 2. select city, population from North_american_cities where country like "%United State%" order by population desc limit 2 offset 2