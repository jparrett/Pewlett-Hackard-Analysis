# Pewlett-Hackard-Analysis
Module 7 - Employee Database with SQL


# Overview
This analysis will look at two reports.    First, it will determine the number of retiring employees per title.    Then, the analysis will identify employees who are eligible to participate in a mentorship program.    These analysis reports will help Pewlett-Hackard prepare for the "silver tsunami" that is expected as a large number of employees are reaching retirment age by anticipating retirement by title then by creating a mentorship program for the company.

# Results: 
The first step in preperation is to determine the number of employees by title that will be retiring.    Employee information was filtered to include only employees with birthdates between January 1, 1952 and December 31, 1955.  Using the fuction, distinct on, this information was updated to include the current title of those employees.   

- The report identified that 90,398 employees will be eligible for retirement.
- Of those employees, 62,170 (68.7%) are employees that hold positions as a leader or senior employee.  
- Senior Engineers hold the highest percentage of retiring employees with 32.5%

<img src="/.../Data/retiring_titles.pdf" width="600"> [retiring_titles.pdf](/.../Data/retiring_titles.pdf)

The next step was to prepare to fill all those positions through a mentorship program.   To obtain this data, the tables were filtered to a list that contained current employees who were born between January 1, 1965 and December 31, 1965.

- The report established a list of 1,549 employees that would be eligible for the mentorship program.
- The report identified that of those employees, 1,098 (70.1%) of employees were already a a senior engineer or senior staff.


# Summary: 
Within the queries, the following was established:

- 90,398 employees will be eligible for retirement.
- 1,549 employees will be eligible for the mentorship program.

The information has given us insight into the future of the company.   Continuing on with these queries can help to develop more understanding about how to build a sustanable company in the future without these large "tsunamis" of retirement.  

- The mentorship program is a wonderful idea, but is currently locked into staff that were born in 1965.    Using a tiered program, start the mentorship program through all employees careers so that employees are constantly receiving mentorship.   More information would be needed from HR to be able to perform this analysis.

- When running the queries, it is known that a large number of the retiring employees are coming from the Production and Development departments.   These departments should be on the top of the list for the estabiling new hiring and mentorship opportunities.

Overall, there are a large number of employees that will be retiring.   Pewlett-Hackard is being proactive by using these queries to better understand the upcoming years and ensure their company is prepared.    Continuation of this data analysis is recommended so that the company can continuously be aware of their staffing levels and mentorship opportunities.


