# Login Bug Reports

## Application: Sample Login Page

| Bug ID | Bug Title | Severity | Priority | Steps to Reproduce | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| BUG_LOGIN_001 | Login button does not respond after entering valid credentials | High | High | 1. Enter valid username and password 2. Click Login | User should be logged in successfully | Login button does not respond | Open |
| BUG_LOGIN_002 | Incorrect error message for invalid password | Medium | Medium | 1. Enter valid username 2. Enter invalid password 3. Click Login | Appropriate password error should be displayed | Incorrect error message is displayed | Open |
| BUG_LOGIN_003 | Password is visible in plain text | High | High | 1. Open login page 2. Enter password | Password should be masked | Password is displayed as plain text | Open |
| BUG_LOGIN_004 | Forgot Password link redirects to incorrect page | Medium | Medium | 1. Click Forgot Password | User should be redirected to password recovery page | User is redirected to an incorrect page | Open |
| BUG_LOGIN_005 | Validation message missing for blank username | Medium | Low | 1. Leave username blank 2. Enter password 3. Click Login | Username validation message should be displayed | No validation message is displayed | Open |
