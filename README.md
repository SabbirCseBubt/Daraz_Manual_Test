# Daraz_Manual_Test
✅ Project Name: Daraz (Frontend)
Client: Daraz
Reference Document: FRS (Functional Requirement Specification)
Testers: Sabbir and Rafi (Group Project)
Creation Date: 2025-10-03

🔍 Testing Scope & Covered Modules:
Module	Description
Register	Tests for user registration with valid, invalid, and missing data.
Login	Covers login with valid and invalid credentials, and system behavior post-login.
Logout	Includes logout action, session timeout handling, and user experience validation.
Search	Verifies visibility and functionality of the search bar and icon with hover states.
Add to Cart	Checks the presence, functionality, and flow of cart operations including "Add", "Continue", and empty cart scenarios.

🧪 Sample Test Case Structure (from all modules):
Field	Example
Test Case ID	TC_RF_001, TC_LF_002, etc.
Test Scenario	Register/Login Functionality
Test Case Title	"Verify that Register an Account by providing only valid phone number"
Pre-requisites	"Open the Application: https://www.daraz.com.bd"
Test Steps	Step-by-step action like click, input, hover, submit
Test Data	Often Not Applicable, but varies with case
Expected Result	Clearly defined expected outcome like successful login, error message, etc.
Actual Result	Matched or deviation from expected result
Priority	P0 / P1 / P2 / P3
Result	PASS / FAIL
Comments	Notes or bug IDs (e.g., DARAZ-BUG-1)

🐞 Bug Tracking Notes:
Issues are tracked using comments like DARAZ-BUG-1, DARAZ-BUG-2 on failing test cases.

📊 Summary of Coverage:
Module	Total Test Cases	Pass	Fail	Notable Bugs
Register	5	3	2	DARAZ-BUG-1, 2
Login	4	4	0	-
Logout	4	3	1	DARAZ-BUG-4
Search	4	4	0	-
Add to Cart	4	4	0	-

✅ Key Manual Testing Features Demonstrated:
Positive & negative testing

UI visibility & interaction testing

Functional flow verification

Bug tracking integration

Priority-based test planning
