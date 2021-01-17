# **Python-Challenge: PyCitySchools**

## Overview
As the Chief Data Scientist for your city's school district, you are tasked with making recommendation to the school board and mayor regarding future school budgets and priorities.

The big focus will be on the district-wide standardized test results from which the recommendations will be based on. The main sources of data will be key information on each of the schools that the students attend **schools_complete.csv** and test result information for each student **students_complete.csv**. In order to properly analyze the data, you must first combine the information and draw key conclusions based on the analysis.

## File Structure

The **PyCitySchools** folder has the following structure:

PyCitySchools:
- Resources
    - schools_complete.csv
    - students_complete.csv
- PyCitySchools_main.ipynb

## Running the Script

1. Verify that the folder and file structure being used on your local directory matches that of the outlined file structure.

2. Open local machine Terminal/GitBash

3. Navigate to the appropriate **PyCity** directory where all of the folders and files are stored. 

4. Input the **jupyter notebook** command and execute in order to bring up the jupyter notebook online computational tool.

## Output

The final report includes each of the following:

### District Summary

- A high level snapshot (in table form) of the district's key metrics, including:
  - Total Schools
  - Total Students
  - Total Budget
  - Average Math Score
  - Average Reading Score
  - % Passing Math (The percentage of students that passed math.)
  - % Passing Reading (The percentage of students that passed reading.)
  - % Overall Passing (The percentage of students that passed math **and** reading.)

### School Summary

- An overview table that summarizes key metrics about each school, including:
  - School Name
  - School Type
  - Total Students
  - Total School Budget
  - Per Student Budget
  - Average Math Score
  - Average Reading Score
  - % Passing Math (The percentage of students that passed math.)
  - % Passing Reading (The percentage of students that passed reading.)
  - % Overall Passing (The percentage of students that passed math **and** reading.)

### Top Performing Schools (By % Overall Passing)

- A table that highlights the top 5 performing schools based on % Overall Passing. Include:
  - School Name
  - School Type
  - Total Students
  - Total School Budget
  - Per Student Budget
  - Average Math Score
  - Average Reading Score
  - % Passing Math (The percentage of students that passed math.)
  - % Passing Reading (The percentage of students that passed reading.)
  - % Overall Passing (The percentage of students that passed math **and** reading.)

### Bottom Performing Schools (By % Overall Passing)

- A table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

### Math Scores by Grade\*\*

- A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

- A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

- A table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  - Average Math Score
  - Average Reading Score
  - % Passing Math (The percentage of students that passed math.)
  - % Passing Reading (The percentage of students that passed reading.)
  - % Overall Passing (The percentage of students that passed math **and** reading.)

### Scores by School Size

- Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type

- Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).
    
## Observations
   
Based on the PyCitySchools script the following obervations were determined:
- Observation 1: Based on the Top Performing Schools (By % Overall Passing), the top 5 performing schools are all charter schools with less than 2300 students, passing rates in math, reading and overall passing rates great than 90%
- Observation 2: Based on the Bottom Performing Schools (By % Overall Passing) the lowest 5 performaing schools have more than 2,900 total students, have a greater passing rate in math as compared to reading, and have overall passing rates near 50%, 40% lower than the top 5 performing schools.
- Observation 3:Based on the Math Scores By Grade, average math grades appear to be be consistent across the 9-12 grade levels at each of the respective schools, meaning that math performace is influenced by the school which the student attends and is constant across grades.
- Observation 4: Based on Scores by School Spending, overall passing rates appear to decrease as the per sudent budget increases, meaning that spending more money per student does not necessarily mean that the student will perform better on standardized testing.
- Observation 5: Based on the Scores by School Size, schools with more than 2000 students see a drastic (nealry 32%) decrease in overall passing rates as compared to medium and smaller schools

## Recommendation

Based on the PyCitySchools analysis, smaller school sizes, rather than larger per student budgets, appear to have a greater positive impact on standardized testing performance. A student is able to receive more focused attention in smaller school sizes, leading to better tes performance.
