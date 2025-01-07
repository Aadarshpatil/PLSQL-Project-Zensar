Loan Management System
Name:-Aadarsh Pravin Patil
Email_Id:-krishishikhawat@gmail.com
Project Overview
The Loan Management System is a comprehensive system designed to manage customer loan applications, approvals, repayments, and associated schedules. This system handles a range of loan types, including personal loans, home loans, car loans, student loans, and business loans, and provides functionalities for customers to apply for loans, track repayments, and update loan statuses based on payment histories.
Features
•	Customer Management: Stores customer details such as name, contact number, and address.
•	Loan Types: Defines different loan types with their respective interest rates.
•	Loan Application: Allows customers to apply for loans by selecting a loan type and specifying the amount.
•	Loan Approval: Enables loan officers to approve or disburse loans after evaluation.
•	Repayment Schedule: Tracks the due dates and amounts for repayments associated with each loan.
•	Payments: Allows customers to make repayments, and updates the status of the repayment schedule accordingly.
•	Loan Status Updates: Automatically updates the loan status to 'Completed' when all repayments for a loan have been made.
Tables
The following tables are included in the database schema:
1.	Customers: Stores information about customers applying for loans.
2.	Loan Types: Defines different types of loans.
3.	Loans: Tracks loan applications and their statuses.
4.	Repayment Schedule: Manages the repayment schedule for each loan.
5.	Payments: Logs the payments made by customers.
6.	Sequences: Ensures unique loan and payment IDs for each transaction.
Stored Procedures & Triggers
•	Procedures: 
o	apply_for_loan: Allows customers to apply for a loan by submitting necessary details.
o	approve_loan: Approves and disburses loans after application.
o	make_repayment: Processes repayments made by customers.
•	Trigger: 
o	update_loan_status: Automatically updates the loan status to 'Completed' when all repayment amounts have been paid.
Prerequisites
•	Oracle Database
•	SQL*Plus or any other Oracle SQL tool (SQL Developer, Toad, etc.)
•	Administrative access to the Oracle database
Setup
1.	Create the Tables: Run the provided SQL script to create tables for customers, loan types, loans, repayment schedules, and payments.
2.	Insert Sample Data: Insert sample records to test the functionality of the system.
3.	Execute the Procedures: You can use the apply_for_loan, approve_loan, and make_repayment procedures to interact with the system.
4.	Use Triggers: Ensure the update_loan_status trigger is properly enabled to automatically update loan statuses.
