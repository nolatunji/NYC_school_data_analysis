# New York City Public Schools SAT Performance Analysis 

## Tools
* SQL
* Jupter Notebook

## Project Description
In this project, I worked with a SQL database containing SAT performance from New York City's public school system.
I analyzed how performance varies by borough, identified how many schools fail to report information, and found the top ten performing schools across the city.

## Data Source

The analysis uses a PostgreSQL database containing a single table 'schools' with the following columns:
- school_name
- borough
- building_code
- average_math
- average_reading
- average_writing
- percent_tested

## Key Findings
- 20 out of 375 schools have missing data for the percentage of students tested
- Through the analysis it was determined that Staten Island has the schools with the highest average test scores followed by Queens and Manhattan.
- Only 10 public schools in NYC have an average math score of at least 640.
- Stuyvesant High School consistently ranks at the top for math, reading, and writing scores.
- Staten Island has the highest average SAT scores, but the smallest number of schools
- The information can be utilzed by district leaders to determine what resources and supports could be used in schools in The Bronx and Brooklyn to increase SAT scores amoungst its student population. 
