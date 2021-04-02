# Pewlett-Hackard-Analysis
Module 7 - Employee Database with SQL


# Overview
This analysis will look at two reports.    First, it will determine the number of retiring employees per title.    Then, the analysis will identify employees who are eligible to participate in a mentorship program.    These analysis reports will help Pewlett-Hackard prepare for the "silver tsunami" that is expected as a large number of employees are reaching retirment age by anticipating retirement by title then by creating a mentorship program for the company.

# Results: 
The first step in preperation is to determine the number of employees by title that will be retiring.    Employee information was filtered to include only employees with birthdates between January 1, 1952 and December 31, 1955.  Using the fuction, distinct on this information was updated to include the current title of those employees.   

- The report identified that 90,398 employees will be eligible for retirement.
- Of those employees, 62,170 (68.7%) are employees that hold positions as a leader or senior employee.  
- Senior Engineers hold the highest percentage of retiring employees with 32.5%

<img src="../Data/retiring_titles.pdf" width="600"> [retiring_titles.pdf](../Data/retiring_titles.pdf)

The next step was to prepare to fill all those positions through a mentorship program.   To obtain this data, the tables were filtered to a list that contained current employees who were born between January 1, 1965 and December 31, 1965.

- The report established a list of 1,549 employees that would be eligible for the mentorship program.
- The report identified that of those employees, 1,098 (70.1%) of employees were already a a senior engineer or senior staff.



# Summary: 
The summary addresses the two questions and contains two additional queries or tables that may provide more insight.

-determine the number of retiring employees per title
-identify employees who are eligible to participate in a mentorship program
