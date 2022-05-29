# Pewlett-Hackard-Analysis
## Project Overview
The main objective of this project is to help Pewlett Hackard Human Resources department analyze the number of employees soon to retire, identify them by department, and help launch training and mentorship programs to develop junior level employees to successfully fulfill those roles in the future; thereby try to reduce negative impact to the company performance in each department when the “silver tsunami” becomes reality.
## Resources
- Data Source: [departments.csv](), [dept_emp.csv](), [dept_manager.csv](), [employees.csv](), [salaries.csv](), [titles.csv]()
- Software: PostgreSQL 11.16 / pgAdmin4
## Results
- ERD (Entity Relationship Diagram) used to visualize the relationship between the data sources and the structure of the company's employee.
![EmployeeDB.png]()
- Based on the retiring titles table, sum of the expected to retire employees are 90,398.
![Sumofexpected to retire.png]()
- A large number of employees of retirement age holding either Senior Engineers (29,414) or Senior Staff (28,254).
![Retiring_titles.png]()
- Mentorship eligible employes count : 402 Engineers, 392 Senior Staff, 332 Staff, 290 Senior Engineers, 77 Technique Leaders, and 56 Assistant Engineers.
![ut_mentorship_eligibilty.png]()
- Based on the mentorship_eligibilty table, sum of the eligible employees are 1,549.
![Sum of mentorship-eligibility.png]()
## Summary
The data indicates 64% of Pewlett Hackard employees are near retirement age which is an alarming fact for any company. This would mean the organization (HR department) has to start actively hiring new employees and engage in employee development programs quickly. Dedicating additional resources and funds to this project could be significant but it would be an investment to ensure the success of the company in the future. Each senior level employee would need to adopt 3 junior level employees as a mentor to provide enough coverage throughout the organization of 13,000 total employees. There are three major departments which would benefit from new hirings as well as the mentorship program the most Development, Production, and Sales… each with 2000 employees or more currently. Since these 3 departments have the most headcount and seem to be the most important departments to Pewlett Hackards performance, the HR department should prioritize them. Remaining departments range around 700 to 800 employees each such as Customer Service, Quality Management, Research, HR, Finance, and Marketing which tend to be supporting departments to company’s core business.  

