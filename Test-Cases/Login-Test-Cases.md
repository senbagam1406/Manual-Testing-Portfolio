# Login Test Cases

## Application: Sample Login Page

| TC ID | Test Scenario | Test Steps | Expected Result |
|---|---|---|---|
| TC_LOGIN_001 | Verify login with valid credentials | Enter valid username and password, click Login | User should be logged in successfully |
| TC_LOGIN_002 | Verify login with invalid password | Enter valid username and invalid password | Appropriate error message should be displayed |
| TC_LOGIN_003 | Verify login with invalid username | Enter invalid username and valid password | Appropriate error message should be displayed |
| TC_LOGIN_004 | Verify login with blank fields | Leave username and password blank, click Login | Validation message should be displayed |
| TC_LOGIN_005 | Verify password masking | Enter password in password field | Password should be masked |
| TC_LOGIN_006 | Verify Forgot Password link | Click Forgot Password | User should be redirected to password recovery page |
| TC_LOGIN_007 | Verify login button | Enter valid credentials and click Login | User should navigate to the home/dashboard page |
| TC_LOGIN_008 | Verify username field accepts valid input | Enter valid username | Username should be accepted |
| TC_LOGIN_009 | Verify password field accepts valid input | Enter valid password | Password should be accepted |
| TC_LOGIN_010 | Verify logout after successful login | Login and click Logout | User should be logged out successfully |
