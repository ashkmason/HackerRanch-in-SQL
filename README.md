## HackerRank Challenges in MySQL
The Following are challenges that I have completed in MySQL

## Weather Observation Station 5
Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.

## Weather Observation Station 6
Query the list of CITY names starting with vowels (i.e., a, e, i, o, or u) from STATION. Your result cannot contain duplicates.

## Weather Observation Station 7
Query the list of CITY names ending with vowels (a, e, i, o, u) from STATION. Your result cannot contain duplicates.

## Weather Observation Station 8
Query the list of CITY names from STATION which have vowels (i.e., a, e, i, o, and u) as both their first and last characters. Your result cannot contain duplicates.

## Weather Observation Station 9
Query the list of CITY names from STATION that do not start with vowels. Your result cannot contain duplicates.

## Weather Observation Station 10
Query the list of CITY names from STATION that do not end with vowels. Your result cannot contain duplicates.


## Weather Observation Station 11
Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.

## Weather Observation Station 12
Query the list of CITY names from STATION that do not start with vowels and do not end with vowels. Your result cannot contain duplicates.

## Higher Than 75 Marks
Query the Name of any student in STUDENTS who scored higher than 75 Marks. Order your output by the last three characters of each name. If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending ID.

## Employee Names
Write a query that prints a list of employee names (i.e.: the name attribute) from the Employee table in alphabetical order.

## Employee Salaries
Write a query that prints a list of employee names (i.e.: the name attribute) for employees in Employee having a salary greater 2000 than per month who have been employees for less than 10 months. Sort your result by ascending employee_id.

## Print Prime Numbers
Write a query to print all prime numbers less than or equal to 1000. Print your result on a single line, and use the ampersand (&) character as your separator (instead of a space).

## Type of Triangle
Write a query identifying the type of each record in the TRIANGLES table using its three side lengths. Output one of the following statements for each record in the table:
- Equilateral: It's a triangle with 3 sides of equal length.
- Isosceles: It's a triangle with 2 sides of equal length.
- Scalene: It's a triangle with 3 sides of differing lengths.
- Not A Triangle: The given values of A, B, and C don't form a triangle.

## The PADS
Generate the following two result sets:
- Query an alphabetically ordered list of all names in OCCUPATIONS, immediately followed by the first letter of each profession as a parenthetical (i.e.: enclosed in parentheses). For example: AnActorName(A), ADoctorName(D), AProfessorName(P), and ASingerName(S).
- Query the number of ocurrences of each occupation in OCCUPATIONS. Sort the occurrences in ascending order, and output them in the following format: There are a totale of [occupation_count] [occupation]s. where [occupation_count] is the number of occurrences of an occupation in OCCUPATIONS and [occupation] is the lowercase occupation name. If more than one Occupation has the same [occupation_count], they should be ordered alphabetically. Note: There will be at least two entries in the table for each type of occupation.

## Occupations
Pivot the Occupation column in OCCUPATIONS so that each Name is sorted alphabetically and displayed underneath its corresponding Occupation. The output column headers should be Doctor, Professor, Singer, and Actor, respectively.
Note: Print NULL when there are no more names corresponding to an occupation.