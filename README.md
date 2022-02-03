# pewlett-hackard-analysis
Module 7: Employee Database with SQL

Employee Database Analysis using PostgreSQL

------------------------------
# Overview of Project
The analysis will determine the number of retiring employees per job title, and identify employees who are eligible to participate in a mentorship program. Goal is to provide  high-level insight into the upcoming "silver tsunami" of retirements to enable company planning. 

## Project Tasks
1. Number of Retiring Employees by Title
2. Employees Eligible for Mentorship Program

## Resources
-- Data Source: multiple .csv files

-- Software: PostgresSQL, Visual Studio


-------------------------------

# Project Results

Analysis Output: 

1. SQL code for multiple queries, as employee_database_challenge.sql file 
2. Four .csv tables (retirement_titles, unique_titles, retiring_titles, mentorship_eligibility) with query results

>
>

# Project Summary

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?

There are approximately 29k Senior Engineers and 28k Senior Staff currently employed that are approaching retirement age as defined for this project (born between 1952 and 1955). There are an additional 14k Engineers and 12k Staff, plus just over 6k employees in other roles (Technique Leader, Assistant Engineer, or Manager). This is a total of 90,398 roles across the company that will need to be filled in the near future. 

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are approximately 1549 employees that meet the mentorship eligibility criteria as defined for this project (born in 1965). This would mean an average of 58 mentees per mentor, which would be very difficult. 
To bring this ratio into a more feasible range, suggest expanding the eligibility criteria to include mentors of a wider age range, perhaps birth dates from 1960 to 1965 or similar. With triple the number of eligible mentors (approx. 4500), this would bring the mentee/mentor ratio to a more feasible 20:1 ratio. Alternatively, if the mentorship timeframe could be staggered (i.e. 20 new mentees each year per mentor with mentees 'graduating' from the mentorship program after a one year timeframe), this could increase mentorship program capacity as well. 

