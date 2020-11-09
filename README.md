# Pwelett_Hackard_Analysis

## Overview of the Analysis
### Purpose
#### There are two purposes for this analysis. The first purpose is to determine the amount of employees that are retiring for each title type. The second purpose is to determine whhich employees are eligible to participate as a mentor in the mentorship program. 

## Results
- From the retirement_titles table, we can see that there are several title under the same employees' name due to promotion. This table also includes employees that have already left the company.
- The unique_titles table provides a list of employees that are retiring with their most recent title (according to the retirement_titles table). 
- The retiring_titles table contains the total amount of employees that are retiring for each title type. It shows that most of the retiring employees are senior engineers, senior staffs, engineers, and staffs. The total number of employees retiring is 90,398. 
- Looking at the mentorship_eligibility table, we can see that most of those who are eligible to participate in the mentorship program are senior engineers and senior staffs. 

## Summary
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  - According to the retiring_titles table, the total number of employees retiring is 90,398. However, if we filter the to_date column in the retirement_titles table we can see that there are only 35,550 employees that are still currently employed and ready to retire. The retiring_titles table included employees that have already left the company before their retirement date. Thus, 35,550 roles need to be filled. 
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  - There is a total of 1549 employees that are eligible to participate in the mentorship program. Comparing this number with the total number of employees retiring, 35,550, we can see that there are not enough qualified and retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. 