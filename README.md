# LOAN MANAGEMENT SYSTEM

## INTRODUCTION:
The Loan Management System (LMS) presented in this abstract is a comprehensive solution designed to streamline and optimize the entire lifecycle of loans. It encompasses a user-friendly interface for seamless loan application, robust approval processes, efficient disbursement workflows, and intelligent repayment tracking mechanisms. The LMS acts as a centralized hub, providing real-time insights into loan statuses, payment histories, and risk assessments. With advanced features such as automated notifications, document management, and risk analysis tools, the system ensures accuracy, transparency, and compliance throughout the lending process.

Click [here](Documents) to view all the content in the Documents.

## DATABASE SCHEMA:
borrowers(id, firstname, middlename,lastname, contact_no,address, email, tax_id, date_created);

loan_list(id, ref_no, loan_type_id, borrower_id, purpose, amount, plan_id, status, date_released, date_created);

loan_plan(id, months, interest_percentage, penalty_rate); loan_schedule(id, loan_id, date_due);

loan_types(id, type_name, description);

payments(id, loan_id, payee, amount, penalty_amount, overdue, date_created); users(id, doctor_id, name, address, contact, username, password, type);

## PROGRAMMING LANGUAGES USED:
1. MY SQL
2. PHP-SERVER SCRIPTING
3. WEB-PAGE DESIGNING:
   - HTML
   - CSS
   - JAVA SCRIPTING

## IMPLEMENTATION STEPS :
1. Install XAMPP
2. Open XAMPP and start all the servers
3. Download the [LMS](LMS) file from the repository
4. Unzip and Move the downloaded file to the XAMPP **htdocs** folder
5. Run the **home.php** file from the **LMS** folder in the web browser
6. Example : http://localhost/LMS/home.php

## IO DATA:
### INPUT DATA:
Customer details (name, address, mobile number, email, etc) and details regarding the loan they want to take (loan type, loan amount, monthly income, etc) is received as the input.
### OUTPUT DATA:
Generated report on Loan Amount payment after verification of customer details from the admin side will be provided to that respective customer.


## SCHEMA DIAGRAM:
<img width="1000" alt="image" src="https://github.com/JagadeeshR14/LoanManagementSystem/assets/139132404/f0d70544-b498-47af-a5d6-3cb1061cbce2">

 
## ENTITY RELATIONSHIP DIAGRAM:
<img width="1000" alt="image" src="https://github.com/JagadeeshR14/LoanManagementSystem/assets/139132404/0faf56e1-6ad9-4d71-96c4-cb4d9dfe1d9a">

Click [here](Diagram) to explore all the Diagrams.

## RESULT:
Click [here](Result) to explore all the screenshot Results/Outputs of the Project.

## CONCLUSION:
The Loan Management System (LMS) is a comprehensive, user-friendly solution designed to optimize the entire lifecycle of loans, from application to repayment. 
With its robust features and functionalities, the LMS provides significant benefits to both customers and administrators.
The well-structured database schema supports the system's functionality, providing a solid foundation for managing borrowers, loan plans, loan schedules, payments, and user information. 
By leveraging this schema, the LMS ensures data integrity and facilitates quick retrieval of information, thereby enhancing operational efficiency.
The LMS enhances interaction and communication between customers and administrators, provides real-time insights, and promotes a paperless environment, making it a valuable asset for any lending institution.




