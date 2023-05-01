# Pewlett-Hackard Analysis
*An SQL HR-Department Analysis*

## Project Overview 
### Purpose
The purpose of this analysis is to prepare Pewlett-Hackard, a company with several thousand employees, for the upcoming “silver tsunami”. A large number of employees will begin retiring at a rapid rate in the next few years and the company wants to be prepared with the retirement packages, open positions and employees’ training. In order to ensure a smooth transition this analysis focuses on the following: 

1.	Identify the retiring employees by their title.
2.	Determine the sum of retiring employees grouped by title.
3.	Identify the employees eligible for participation in the mentorship program.
4.	Determine the number of roles-to-fill grouped by title and department.
5.	Determine the number of qualified, retirement-ready employees to mentor the next generation grouped by title and department.


<p align="center">  
<img src="Graphics/cityatnight.PNG" width="60%" height="60%">
</p>


### Background
The data is gathered in six CSV files and the analysis is performed using relational databases. In this analysis I am using:
- **QuickDBD** to create quick database design for better visualization,
- **PostreSQL** a database system to load, build and host company’s data, and 
- **pgAdmin** a GUI, using SQL Language to explore, manipulate and extract the data. 

As a part of **data modeling** and **data engineering** the fundamental knowledge of constraint rules and awareness of “dirty data” that is flawed and require extensive cleaning is very important. A section in the module summarizes few rules when building the database:

> A constraint is a rule that is applied to a column in a SQL table. It will limit the data in a way that provides more accuracy and reliability when working with it. The unique constraint implies that the data in that column is unique. This ensures that if the table were to be updated in the future, nothing will be duplicated (1). 


