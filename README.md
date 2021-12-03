# Lint Financial Planning

Project Description: Lint is a web-based financial-planning application that is used for creating categorized budgets, tracking bill amounts & due dates, and analyzing transaction histories.   
  
Technologies Used: Java, Hibernate, Angular 13, Selenium IDE, Spring Boot, Spring Data, AWS RDS, Swagger, Lombok, REST, JUnit, Karma & Jasmine, Protactor, Mockito, PostgreSQL  
  
Features:
1. Login - A user may log into their User Account with a valid Username & Password combination  
2. Create Budget - A user may create, edit, and track budgets with assigned spending categories and durations  
3. Connect Account(s) - A user may connect Bank/Credit accounts to their User Account  
4. View Transactions - A user may view transaction histories related to their connected Bank/Credit accounts  
5. View Bills - A user may add and track the balances/due dates of bills associated with their User Account  
6. Transaction Analysis - A user may view records and statistics related to their spending/income such as amount spent within a given time period, average monthly income, total net gain/loss, spending by category, spending by merchant  
  

Getting Started:   
Database: Start AWS RDS with the database information found in the < application.properties > file found inside the 'Lint Financial Backend' project folder  

Backend: Run < Project2Appication.java > inside a Java IDE or command line inside the 'Lint Financial Backend' project folder  

Frontend: Run command < ng serve -o > in command line inside the 'Lint Financial Frontend' project folder  
  

Usage:  
Application is in unfinished state. Data manipulation must be done directly inside database or manually following Controller URLs  

Navigate to http://localhost:4200/ in a web browser to the login page  
Navigate to http://localhost:4200/users/ to see the User homepage where Accounts, Bills, and Transactions are listed  




