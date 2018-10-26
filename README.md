#FSDC


An abstract portal to enter peer reviews from employees


1) On starting, 
a login page appears where employees give their username and password to login.

sample usernames and passwords:

username password

adunphy   AlexDunphy
mmahoney  MollyMahoney
dtippens  DmitriTippens

2) After logging into their profile, it redirects to a page to submit their evaluation for default employee "Dmitri Tippens(dtippens)"


Database and Tables

Db used : SQL Server 2014
Authentication mode : Windows authentication
Database name : FSDC_Employee_DB

Tables

1) emp_details

emp_id , first_name ,last_name, username, email_id, department, designation, project_title

2) emp_login

emp_id, first_name, last_name, username, pwd

3) emp_review_actions

emp_id, pending_reviews, submitted_reviews

note : pending_reviews is the ID's of peers whose evaluation is pending

	submitted_reviews is the total number of reviews subitted so far


Front End : ASP.net 

Microsoft Visual Studio 2017

  