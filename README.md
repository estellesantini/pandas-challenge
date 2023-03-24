# pandas-challenge


# Background

In this scenario, I put myself in the position of a Chief Data Scientist for a city's school district. In this capacity, I would be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I've been asked to analyze the district-wide standardized test results. I was given two csv. files: schools_complete and students_complete that I combined into a single dataset. I was given access to every student's math and reading scores, as well as various information on the schools they attend. 

My task was to aggregate the data to showcase obvious trends in district and school performance. This challenge applies what I have learned in Pandas including GroupBy functions, bins, DataFrames, and conditionals.


# Calculations
In this report, I performed calculations on the following metrics:
### District Summary
    - Total number of unique schools
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading
    - Created DataFrame district_summary
### School Summary
    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)
    - Created DataFrame per_School_summary
### Highest Performing Schools by Percentage of Overall Passing
    - Sort the schools by % Overall Passing (>= 70%) in descending order
    - Created a DataFrame called top_schools
### Highest Performing Schools by Percentage of Overall Passing
    - Sort the schools by % Overall Passing (>= 70%) in ascending order
    - Created a DataFrame called bottom_schools
### Math and Reading Scores by Grade
    - Created two DataFrames that list the average math scores and the average reading scores for students of each grade level (9th, 10th, 11th, 12th) at each school.
### Scores by School Spending, School Size, and School Type
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)
    - Created one DataFrame for each GroupBy function


