# IMDB-Movie-Dataset
Q1 --- List all the directors who directed a 'Comedy' movie in a leap year.
(You need to check that the genre is 'Comedy’ and year is a leap year)
Your query should return director name, the movie name, and the
year.
To determine whether a year is a leap year, follow these steps:
STEP-1: If the year is evenly divisible by 4, go to step 2. Otherwise, go to step 5.
STEP-2: If the year is evenly divisible by 100, go to step 3. Otherwise, go to step 4.
STEP-3: If the year is evenly divisible by 400, go to step 4. Otherwise, go to step 5.
STEP-4: The year is a leap year (it has 366 days).
STEP-5: The year is not a leap year (it has 365 days).
Year 1900 is divisible by 4 and 100 but it is not divisible by 400, so it is not a leap year.


Q2 --- List the names of all the actors who played in the movie 'Anand'
(1971)


Q3 --- List all the actors who acted in a film before 1970 and in a film
after 1990. (That is: < 1970 and > 1990.)


Q4 --- List all directors who directed 10 movies or more, in descending
order of the number of movies they directed. Return the directors' names
and the number of movies each of them directed.

Q5.a --- For each year, count the number of movies in that year that had
only female actors.

Q5.b --- Now include a small change: report for each year the percentage
of movies in that year with only female actors, and the total number of
movies made that year. For example, one answer will be: 1990 31.81
13522 meaning that in 1990 there were 13,522 movies, and 31.81% had
only female actors. You do not need to round your answer.

Q6 --- Find the film(s) with the largest cast. Return the movie title and the
size of the cast. By "cast size" we mean the number of distinct actors
that played in that movie: if an actor played multiple roles, or if it simply
occurs multiple times in casts, we still count her/him only once.

Q7 --- A decade is a sequence of 10 consecutive years.
A decade is a sequence of 10 consecutive years. For example, say in your database you
have movie information starting from 1965. Then the first decade is 1965, 1966, ..., 1974; the
second one is 1967, 1968, ..., 1976 and so on. Find the decade D with the largest number of
films and the total number of films in D.

Question 8:
Find the actors that were never unemployed for more than 3 years at a
stretch. (Assume that the actors remain unemployed between two
consecutive movies).

Q 9--- Find all the actors that made more movies with Yash Chopra than
any other director.

Q10 --- The Shahrukh number of an actor is the length of the shortest
path between the actor and Shahrukh Khan in the "co-acting" graph.
That is, Shahrukh Khan has Shahrukh number 0; all actors who acted in
the same film as Shahrukh have Shahrukh number 1; all actors who
acted in the same film as some actor with Shahrukh number 1 have
Shahrukh number 2, etc. Return all actors whose Shahrukh number is
2.
