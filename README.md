Project Objective/Problem Statement:-
Help an Organization to improve employee performance and improve employee retention(reduce Attrition) by creating a HR Analytics Dashboard.
Which are the important or key factors that helps us to ascertain as top why employees are leaving the company?


KPI'S-

KPIs means performance indicators, this is a sum review of the entire dashboard and how these KPIs are decided,so first of all I told you how many number of employees are there in the company, then the second Attrition, Attrition means how many people have left this company, that is Attrition, second Attrition rate, so according to this Attrition, I have calculated the Attrition rate, then comes The average age is what is the average age of our employees.


Data Cleaning & processing:-

-Removing null values
-Removing Duplicates
-Changing Data type

Project Key Points/DAX function used:-

On the data we have only "Yes" or "No" under the Attrition column.Therefore,we cannot assign a value to it on the dashboard.
In order to assign a value,I have created a new conditional column by the name"Attrition Count" by using IF Function.
Now, we have the count-237 Employees.
To get a better insight,we have to also calculate the "Attrition Rate":-
-To create an Attrition Rate Column,I have used the New Measure using SUM function:-
   Sum(HR_Analytics[Attrition Count]/Sum(HR_Analytics[Employee Count])

Formula used to derive aforsaid funcation:-

Total Attrition/Total Employee

Visualization(Charts & Tables) Used:-
-Donut Chart
-Stacked Column chart
-Matrix
-Bar Chart
-Area Chart
-Tree Map

Summary:-

Attrition, Attrition means how many people have left this company, that is Attrition, second Attrition rate, so according to this Attrition, we have calculated the Attrition rate, then comes The average age is what is the average age of our employees working in the company, what is their average salary, after that comes the airside company, which means how many years the employee has worked with us on an average, which is 7 years, which is a very good number and at the last I have put a chart in the form of KPI, which will tell you the distribution between male and female and then the next chart you can see here is telling that in the education field, that is, the educational background of the employees who are leaving our company was done, after that the next chart you have is addition by today, here I have made a group of age like in twenty six to thirty five, the maximum number of people have left this company, how many people have left one hundred and sixteen, which is a big number, like this here you will get another table, in this table we are telling about different job roles and according to that, you see here one two three four some courses are given, so this score means job certification score And on that basis, what scores did the people give and how many people left the company, that detail is available here, after that, it comes to you how many people left on the basis of salary slab.
So you can see that most of the people who left the company had a salary of Rs 5000 or less, so this is one reason, it is a very big reason for leaving the company, after that comes the addition by year, the number of years people worked in the company and then left it, so if you see, most of the people who are leaving are leaving in the second year, that means before the first second year, if you see, most of the people are leaving within the first year itself which is fifty nine and similarly if you see after 10 years, as it completes 10 years in the company, then people leave, 18 people leave and in between there is one more place when it becomes 5 years.

After that, the last chart that we made is on the basis of job role. Here you can see like lab technician, sales executive, research scientist, sales, so how many people are leaving, their number is given here. So this is my complete dashboard on which I have worked upon as a project.







