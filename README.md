# Project-One
Expense Reimbursement System (ERS)

The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for 
expenses incurred while on company time. All employees in the company can login and submit requests 
for reimbursement and view their past tickets and pending requests. Finance managers can log in and 
view all reimbursement requests and past history for all employees in the company. Finance managers 
are authorized to approve and deny requests for expense reimbursement.

The back-end system connect to a Postgres database
• The backend also use Javalin technology for processing incoming HTTP requests and 
providing an appropriate HTTP response for each endpoint
• The front-end view can use HTML, CSS, and JavaScript (multi-page application) that uses the 
Fetch API to call server-side (backend) components
• Users can upload a document or image of their receipt when submitting reimbursements
• Unit testing code coverage using JUnit 5 for the Service layer 
• Selenium tests for all major functionality (logging in as a user, logging out, logging in as a finance manager 
and Employee
