# Pewlett-Hackard Analysis

## Overview of Analysis

Pewlett-Hackard is a large company with several thousand employees and many of them are reaching retirement. The retirement will leave thousands of job openings. In order to prepare for this, Pewlett-Hackard will need to determine who will be retiring in the next few years and how many positions need to be filled. SQL was used to determine the number of retiring employees per title and to identify employees that are eligible for a mentorship program that Pewlett-Hackard is offering.

## Resources

- Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv (in the Data folder)

- Software: PostgreSQL, pgAdmin, Visual Studio Code

## Results

To determine the number of employees retiring per title only those that were born between the years 1952 and 1955 were included. This makes the assumption that those born between 1952 and 1955 will be retiring soon.

![Retiring Titles](https://github.com/albertomontilla17/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.png)

- There were 90398 employees who were about to retire in Pewlett Hackard.

- For employees who were ready to retire, the detailed title information was as follows: There were 29414 Senior Engineers, 28254 Senior Staff, 14222 Engineers, 12243 staff, 4502 Technique Leaders, 1761 Assistant Engineers, and 2 Managers.

- The most vacant positions in the company would be Senior Engineer, Senior Staff, and Engineer since most people were retiring in these three titles.

- 1549 current employees who were about to retire were eligible for the Mentorship Program.

## Summary

1.According to this analysis 90,398 roles will need to be filled as the "Silver Tsunami" begins. However, this analysis didn't sort for current employees.

2.There are 1,549 employees in the pool for mentorship. The pool of qualified, retirement-ready employees in the related departments far exceed this, and therefore there are enough employees to mentor the next generation of pewlett Hackard employees.

