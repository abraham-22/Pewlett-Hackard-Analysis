# Pewlett-Hackard-Analysis

## Overview of the analysis: 
Pewlett-Hackard offering a retirement package for their aging employee who meet a criteria. The company also starting to plan about future hiring process in which positions will need to be filled due to the upcoming retirements.The overall purpose of this analysis is to answer to find out who will be retiring in the next few years? And how many positions will the company need to fill? The analysis will provide a list of all employees eligible for the retirement package.

## Resources: 
Data Sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
Software: SQL, PostgreSQL, pgAdmin


## Results: 
* Pewlett Hackard has a lot of employees getting ready to age out of the program. AS shown below in Unique Title Table, among total retiring employees more than 50% of them are Engineers, senior staff and experinced employees. The mentoring program, however, will help retain some of the experienced employees as part-time role instead of retiring completely. Mentorship Eligibility Table shown below.

![image](https://user-images.githubusercontent.com/114262970/203775948-213ca94b-044a-423b-b668-67bc9e2441be.png) ![image](https://user-images.githubusercontent.com/114262970/203778805-b376ea51-197f-4d96-bb72-10f036dcb7d0.png)

The table show below (position_to_fill table), indicates that the largest number of retirees coming from two departments, production and development. The senior engineer in these two departments accounts approximately 30% of the total upcoming retirements.
![image](https://user-images.githubusercontent.com/114262970/203791579-c7905018-7aab-40d5-bcf9-fe9e3dc91102.png)

## Summary:
Pewlett Hackard is facing an upcoming "silver tsunami" baby boomers retirements. This will have a huge impact on the company's future success. To avert unwanted consquence due to this "tsunami" of retirments, a strong employee research and planning is vital. The number of upcoming retirements will leave thousands of job openings. As a result, we build employee database with SQL by applying data modeling, engineering, and analysis skills. Among the different generated reports, position_to_fill table above give a good insight about the number of the employees that are about to retire per job title per department. The code shown below used to generate this information.


 <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/114262970/203798035-2b177049-d540-4eba-80eb-8290775b792b.png">

The code shown below gave us the answer the second question in our objective, how many positions will the company need to fill?. The below code is used to count the number of upcoming retirements per departments. As it is shown above, the analysis results helps to points the direction of the future extensive hiring process by the company in the upcoming years. 

![image](https://user-images.githubusercontent.com/114262970/203798884-2d76a114-3c98-497d-b623-a84442860582.png)

