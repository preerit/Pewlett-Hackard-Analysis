# Pewlett-Hackard-Analysis

## Overview
Pewlett Hackard is a large company boasting several thousand employees. The number of retirees in the organization is rapidly increasing ("silver tsunami"). The company is planning to deal with the situation in 2 ways - 
* By offering retirement package for those who meet certain criteria
* Which positions might need to be filled in the near future
Our analysis will help prepare P-H for the future, where mass retirement will result in thosands of job openings. The analysis mainly focuses on employee research, sepcifically anaswering the question of who will be retiring in the next few years and how many posiitions need to be filled. This will help future proof P-H. 
The tool that is used for the analysis is SQL. Conceptual, logical and physical ERD's are built with 6 csv files to understand linkages between datasets. Using this information and SQL, we are analysing data for the findings we want to discover.
Key focus area of the challenge assignment: Determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

---

## Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
![retiring_titles_image](https://github.com/preerit/Pewlett-Hackard-Analysis/blob/main/ritiring_titiles_image.png)
* The number of senior engineers and senior staff retiring are higher than other positions - so there could be a shortage of senior tech employees soon

![mentorship_eligibility_image](https://github.com/preerit/Pewlett-Hackard-Analysis/blob/main/mentorship_eligibility_image.png)
* Mentorship eligibility outcome indicates that senior staff and engineers satisfy the criterion of eligibility while the future shortage could also be for senior engineers. Only ~169 senior engineers satisfy the mentorship eligibility criterion

---

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
~ 72,458 roles need to be filled as the "silver tsunami" begins to make an impact on Pewlett Hackard
### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
There does not seem to be enough retirement-ready employees in the departments to mentor the next generation. There is a total of ~1,549 employees who satify the mentorship eligibility criterion. Number of employees per role is also significantly less than the need of the hour!
### Two additional queries
* In deliverable 2, count() per role for employees who are eligible for mentorship
* In deliverable 1, group by experience in the company to better understand the average tenure at P-H
