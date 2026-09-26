Manual Testing Project — E-Commerce Web Application
📌 Project Overview
This project demonstrates a complete Manual Software Testing process performed on an E-Commerce Web Application.
The objective of this project was to apply real-world QA practices throughout the software testing lifecycle, including test planning, test scenario creation, test case design, test execution, defect reporting, requirements traceability, and test summary reporting.
The project focuses on validating the application's major user workflows and identifying functional and UI issues through structured manual testing.

🎯 Testing Objectives
The main objectives of this project were to:
Validate the functionality of the application's major user workflows.
Identify functional, UI, validation, and usability issues.
Design and execute structured manual test cases.
Verify application behavior against defined testing requirements.
Document and report identified defects.
Perform retesting where required.
Maintain requirements-to-test traceability.
Prepare a final test execution summary.

🛒 Application Under Test
Application Type: E-Commerce Web Application
The application was tested from the perspective of different user workflows, including:
User Login
Product Listing
Product Sorting
Shopping Cart
Checkout
Order Confirmation
Logout
Additional User/Account Testing

🔍 Testing Scope
Functional Areas Tested
Login and authentication
Product listing and product information
Product sorting
Add to Cart functionality
Shopping Cart management
Checkout workflow
Customer information validation
Order submission
Order confirmation
Order PDF generation
Logout and session behavior
End-to-End user workflows
Additional user/account behavior
Testing Types
Functional Testing
UI Testing
Regression Testing
Exploratory Testing
Validation Testing
End-to-End Testing
Retesting
Negative Testing

🧰 Tools & Technologies
Tool / Technology

Google Sheets - Test scenarios, test cases and test execution
Google Docs - Test documentation and bug reports
Web Browser - Application testing


👥 Test User Accounts
Testing included multiple user accounts with different application behaviors:
standard_user — General functional testing
locked_out_user — Authentication and access testing
problem_user — Product and cart behavior testing
performance_glitch_user — Performance-related testing
error_user — Error and functional behavior testing
visual_user — UI and visual testing

📊 Test Execution Summary
A total of 148 test cases were executed during the testing process.
Metric
Result
Total Test Cases - 148
Passed - 113
Failed - 8
Blocked - 27
Defects Identified - 7

The blocked test cases were primarily related to functionality or expected behavior that could not be verified because the required specification, field, functionality, or measurable acceptance criteria was not available.

🐞 Defect Testing
Defects identified during testing were documented with relevant information such as:
Defect ID
Defect title
Environment
Preconditions
Steps to reproduce
Expected result
Actual result
Severity
Priority
Defect status
Related test case
The defect documentation is available in the Bug-Reports folder.

🔗 Requirements Traceability
A Requirements Traceability Matrix (RTM) is included to establish traceability between:
Requirements → Test Cases → Test Results → Defects
The RTM helps demonstrate that the defined requirements are covered by the executed test cases.

📁 Project Structure
Manual-Testing-Project/
│
├── README.md
│
├── Test-Plan/
│   └── Test-Plan
│
├── Test-Scenarios/
│   ├── Login
│   ├── Product-Listing
│   ├── Product-Sorting
│   ├── Shopping-Cart
│   ├── Checkout
│   └── Logout
│
├── Test-Cases/
│   └── Test-Cases
│
├── RTM/
│   └── RTM
│
├── Bug-Reports/
│   └── Bug-Reports
│
└── Test-Summary/
    └── Test-Summary


🔄 QA Process Followed
The project followed a structured manual testing workflow:
Requirements Analysis
        ↓
Test Planning
        ↓
Test Scenario Design
        ↓
Test Case Design
        ↓
Test Data Preparation
        ↓
Test Execution
        ↓
Defect Identification
        ↓
Defect Reporting
        ↓
Retesting
        ↓
Regression Testing
        ↓
Test Summary


🧠 Key QA Activities Performed
During this project, I practiced and demonstrated:
Requirements analysis
Test scenario design
Test case design
Positive and negative testing
Boundary and validation testing
Functional testing
UI testing
Exploratory testing
Regression testing
End-to-End testing
Defect identification
Defect documentation
Severity and priority classification
Retesting
Requirements traceability
Test execution reporting

📈 Key Findings
The testing identified several functional and UI-related issues across the application, including issues related to:
Empty-cart checkout behavior
Customer information validation
Product image display
Cart functionality for specific user accounts
Product page UI behavior
Visual layout and alignment
All identified defects were documented and linked to the relevant testing evidence.

📋 Project Deliverables
Deliverable
Description
Test Plan
Defines testing objectives, scope, approach and resources
Test Scenarios
High-level scenarios covering application functionality
Test Cases
Detailed test cases with expected and actual results
RTM
Maps requirements to test cases and defects
Bug Reports
Detailed documentation of identified defects
Test Summary
Final test execution results and findings


👩‍💻 About This Project
This project was created as part of my QA portfolio to demonstrate practical knowledge of Manual Software Testing and the application of QA methodologies in a real-world style testing environment.
It reflects my approach to analyzing requirements, designing test coverage, executing tests, identifying defects, performing retesting, and documenting testing results.

🚀 Future Improvements
Planned areas for further development include:
API testing using Postman
SQL-based database validation
Automated UI testing
Test automation framework development

