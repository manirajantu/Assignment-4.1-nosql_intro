# Introduction to NoSQL: Assignment

## Brief

In the assignment submission, you will conclude your findings presented over zoom.

### Question 1 - Which use case your (temporary) group was working on?

```
// Your answer

case 1
case 2
case 3

```

### Question 2 - Summarize your solutions and the database(s) used (you may incorporate feedback from instructor and produce a personal conclusion)

```
// Your answer

Case study 1

Database Recommendation: NonSQL (MongoDb)

Reason: 
Set-up horizontally by region. So that can be intercepted into any negative review by not spreading it to other part of the world and address it to change to positive. Manage and control by region.

Example:

Drop table if exists links;

Create table links (
	Id serial primary key,
	first_name varchar(255) not null,
    last_name varchar(255) not null,
    description varchar(255),
    last_update date
);

Output:
_id	    first_name     	last_name    	description     last_update
1	     Mani	          Raja     	    (null)	          20220314
2	    Scott	          Morris     	(null)            20220314


Case study 2:

Database Recommendation: SQL (Postgress)

Reason:
As there requirement for relational keys to be assigned by regional.

Example:

sql = "INSERT INTO `employee` (`EmployeeID`, `Ename`, `DeptID`, `Salary`, `Dname`, `Dlocation`) VALUES (%s, %s, %s, %s, %s, %s)"

Output:
(1001, 'John', 2, 4000, 'IT', 'New Delhi')
(1002, 'Anna', 1, 3500, 'HR', 'Mumbai')
(1003, 'James', 1, 2500, 'HR', 'Mumbai')



Case study 3: 
Database Recommendation: Wide-Column (Casandra)

Reason: Performance is the key factor here with consistence, reliability & availability.

Example: 


cqlsh:tutorialspoint> INSERT INTO emp (emp_id, emp_name, emp_city,
   emp_phone, emp_sal) VALUES(1,'ram', 'Hyderabad', 9848022338, 50000);


Output:
emp_id	emp_name	emp_city	emp_phone	emp_sal
1	     ram	   Hyderabad	9848022338	50000
2	    robin	   Hyderabad	9848022339	40000








```

### Question 3 - Please replicate the data format you have used in the following code block.

```
// Paste your sample data here






```

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
- Submit your assignment to black board.
