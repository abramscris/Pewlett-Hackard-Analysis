# Pewlett-Hackard-Analysis

## Overview of Project

This project has the purpose of analize the Database for Pewlett Hackard with focus on the future retirees that are currently employee in the company and help with the preparation and anticipation for the hiring process of new employees and mentorship initiative.
 
## Results

In order to help extract the current number of employees that are include on the criteria of retirement we refined the data and we could identify the following considerable information:

•	Representing 50.2% of retiring population it was identified staff that had “Engineer” in the title and 44.8% retirees that have “Staff” on their title job. The last around 5% are qualified on Technique Leaders and Managers.
•	After conclude analysis it was found that 1,940 employees are eligible to be mentors in the mentorship program.
•	It was extracted the total of 90,398 employees up to retirement.
•	There are roughly 2 mentors for every 90 vacancies.

* The following chart shows teh Retiring Titles count
<img src="https://github.com/abramscris/Pewlett-Hackard-Analysis/blob/master/Images/unique_titles.png">

* This table shows the first 10 rows of employees elegible to particpate in a mentorship program, the full table has 1,940 rows.
<img src="https://github.com/abramscris/Pewlett-Hackard-Analysis/blob/master/Images/mentorship_eligibility.png">

## Summary
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?

In total, as mentioned previously, there is 90,398 roles that will need to be filled as the employees reach the retirement age. We can extend this analysis creating a new query identifying the total number of employees are 300,024 and then concluding that the future retirees represent 30% of the company.


*	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?


As per this research we can conclude that the number of mentors is not enough to fulfill the next generation employees needs. As we discover there is only 2 mentors for every 90 new employees representing a total of 1,940 employees eligible for the mentoring, also it will need to be considered the employees that are not willing to participate.
In conclusion as the high volume of future employee’s retirement approaches the company should look for different solutions for mentorship such as hiring a third party to be in contact with the professional while they are still employee in the company, internal researches to quantitative interest in participation of current employees and create a new plan for the upcoming generation in order to avoid this to repeat on the future.

## Resources
departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

Software: SQL, PostgreSQL, pgAdmin
