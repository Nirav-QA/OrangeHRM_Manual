# OrangeHRM_Manual
This repository contains the manual testing report for the Login Page of the application. The testing was conducted to ensure the functionality of the login process, focusing on valid and invalid inputs for both username and password fields.
Test Scenarios Covered:
Valid username and password login
Invalid username and password login
Username with special characters
Password length validation
Error message display for incorrect login credentials
Bug Found:
During testing, a critical bug was identified:
Issue: After entering an incorrect username, the system still allows login.
Severity: Critical
Priority: High
Steps to Reproduce:


Enter an invalid username (e.g., testuser123).


Enter a valid password.
Click "Login".

Expected Result: The system should display an error message stating "Invalid username or password".
Actual Result: User is logged in successfully despite entering an invalid username.


Test Environment:
Browser: Google Chrome, Version 90
OS: Windows 10
Device: Desktop
This bug was reported to the development team for fixing."
