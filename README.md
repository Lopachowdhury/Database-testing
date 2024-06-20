
# Database Testing with MySQL

A brief description of what this project does and who it's for


## Table of Contents
1.Introduction 

2.Prerequisites

3.Table Structures

4.SQL Query for Database Testing
## Introduction
This document provides a comprehensive guide to testing a MySQL database using queries. Effective database testing ensures that data is accurately stored, retrieved, and maintained, supporting the overall integrity of the database.

## Prerequisites


- MySQL Server: Installed and configured.
- MySQL Client: Such as MySQL Workbench, or any SQL command-line tool.
- Test Database: A sample database or the database you intend to test.
- Access Credentials: User credentials with sufficient privileges to perform testing.
- SQL Knowledge: Basic understanding of SQL and database concepts.
## Table Structures
- Employee: Contains details of employees.
- Salary: Holds salary information of employees.
- Department: Stores department details.
- Location: Provides location details.
- Job: Contains job roles and related information.
### Employee Table Structure

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/46a9f13b-beaf-44bf-aad6-bc98fcde6eb8)

### EMP Table
![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/f261f9e7-17ca-4299-9a34-c2d4c7a2c5f3)

### Salary Table Structure
![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/7648f100-59d0-49d6-bbfc-5c9da033dfed)
### Department Table Structure
![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/b045b2d6-f721-45d8-a021-80b4f1281375)
### Location Table Structure
![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/ed6050a9-7b74-4ec5-ab3d-9a9f41b654eb)
### Job Table Structure
![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/8075512c-4a8c-4d4f-a91e-9be2930596d1)
## SQL Query for Database Testing
This document provides a series of SQL queries designed for testing various operations on a database containing employee and salary data. Each query is accompanied by an explanation of its purpose and its SQL syntax.

### Contents
1.Fetch Employees by Manager

2.Fetch Distinct Projects

3.Count Employees in a Project

4.Salary Statistics

5.Employees with Salary in a Range

6.Employees in Chennai Under a Manager

7.Employees in Chennai or Under a Specific Manager

8.Employees Not in Project 'P1'

9.Total Salary Including Variable

10.Employees with Specific Name Pattern

11.Employees Without Commission

12.Employees in Department 10 with Salary Above 3500

13.Employees Ordered by Salary

14.Employee Count by Department

15.Departments with At Least 3 Employees

16.Employees with Maximum Salary

17.Employees in Sales Department

18.Employees in New York

19.Update Salaries for Managers

20.Delete Salespersons

21.Display Highest Salary

22.Display Second Highest Salary

23.Display Nth Highest Salary
### Query Details
1. Fetch Employees by Manager
Query:
Fetch the EmpID and Name of all employees working under a manager with ManagerId of 986.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/5d87bec0-51f3-40f5-a80e-83dd700a13b7)

2. Fetch Distinct Projects
Query:
Fetch the distinct projects available from the Salary table.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/56517716-0523-455d-bf78-622dc1765db7)


3. Count Employees in a Project
Query:
Fetch the count of employees working on project 'P1'.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/abb876ab-1a5f-4704-86ce-b49f3fcfa37e)


4. Salary Statistics
Query:
Find the maximum, minimum, and average salary of the employees.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/2b69e06d-d787-4b01-9acc-a0694c73fe85)

5. Employees with Salary in a Range
Query:
Fetch the employee IDs of those whose salary is between 30000 and 40000.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/ba719c3e-bd80-40e2-b27e-7ae8da5dc155)


6. Employees in Chennai Under a Manager
Query:
Fetch the details of employees who live in Chennai and work under the manager with ManagerId 986.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/0ebd37ce-f452-414a-a38b-783c223232a1)



7. Employees in Chennai or Under a Specific Manager
Query:
Fetch the details of employees who either live in Chennai or work under a manager with ManagerId 321.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/850dc5ce-b1c8-4a27-bde9-9daf0c42c336)



8. Employees Not in Project 'P1'
Query:
Fetch the EmpId of employees who work on projects other than 'P1'.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/e79bbcf1-accc-43d2-915b-9c9233af8e7d)

9. Total Salary Including Variable
Query:
Display the total salary of each employee by adding the Salary with Variable value.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/f7de2230-46c6-4bf5-84c6-14e478ae7959)


10. Employees with Specific Name Pattern
Query:
Fetch employees whose names begin with any two characters, followed by 'vi', and ending with any sequence of characters.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/f59b2839-3aeb-4eee-a9ca-79f2c15c973c)



11. Employees Without Commission
Query:
List the employees who are not receiving a commission.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/311a0b29-7b53-4b16-98ec-5cc4a072ad98)

12. Employees in Department 10 with Salary Above 3500
Query:
List the employees working in department 10 who earn a salary of more than 3500.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/1c042c08-a2c4-49b8-9c16-8f9c3537239a)


13. Employees Ordered by Salary
Query:
List the employee ID and name in descending order based on the Salary column.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/c6f441bd-3f5f-4f2f-9a10-639a0226c00f)


14. Employee Count by Department
Query:
Count the number of employees working in each department.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/4b4bf19c-5ee5-4ad2-bae8-da597e538683)


15. Departments with At Least 3 Employees
Query:
List the department IDs having at least 3 employees.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/c3ebe1b9-e81f-4987-a1a9-29dc2fc78dc8)

16. Employees with Maximum Salary
Query:
Fetch the details of employees who have the maximum salary.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/a3754412-5dc1-49b5-b0bb-4074f95fb221)

17. Employees in Sales Department
Query:
Fetch the details of employees who are working in the Sales department.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/78e3a5e8-673e-491d-9375-3530707407e9)

18. Employees in New York
Query:
Fetch the details of employees who are working in "New York".

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/3a96912d-6f94-4939-8eb5-0be929c91de8)

19. Update Salaries for Managers
Query:
Update the salaries of employees who are working as Managers by 10%.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/5d6f83a4-6642-4d4c-9bfc-b1437a830537)


20. Delete Salespersons
Query:
Delete employees who are working as Salespersons.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/ce0cf1fe-74b2-48b2-b8bc-1bfa49c51ad7)

21. Display Highest Salary
Query:
Display the highest salary from the employee table.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/bf5c3d25-ae22-41f3-860d-2ac8150b8902)

-- Alternative way

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/50dfa6b6-5e4e-46d5-994a-d33b30c5aa31)


22. Display Second Highest Salary
Query:
Display the second highest salary from the employee table.

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/70f15023-b762-4bd9-a4d9-00fc29bfcaf8)

-- Alternative way

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/d884bc8d-afd5-4a9d-8991-f0a582f867f8)


23. Display Nth Highest Salary
Query:
Display the Nth highest salary from the employee table. For example, to fetch the 3rd highest salary:

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/73c7af5a-0861-4db4-ae27-66427718b22e)

-- Alternative way

![image](https://github.com/Lopachowdhury/Database-testing/assets/139904174/5b88d3c0-74d6-4518-8d96-cd62efc99285)
