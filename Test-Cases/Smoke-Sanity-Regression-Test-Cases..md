# Smoke, Sanity & Regression Testing

## Application
Sample Web Application

## Smoke Testing

Smoke testing is performed to verify that the critical features of the application are working after a new build is deployed.

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| SMK_001 | Verify application launches successfully | Application should open without errors |
| SMK_002 | Verify login with valid credentials | User should login successfully |
| SMK_003 | Verify main dashboard loads | Dashboard should load successfully |
| SMK_004 | Verify navigation menu | All main menu options should work |
| SMK_005 | Verify logout | User should be logged out successfully |

## Sanity Testing

Sanity testing is performed after minor changes or bug fixes to verify that the affected functionality is working correctly.

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| SAN_001 | Verify fixed login issue | Login should work correctly |
| SAN_002 | Verify password validation | Correct validation message should appear |
| SAN_003 | Verify Forgot Password | User should be redirected correctly |
| SAN_004 | Verify login after password reset | User should login successfully |
| SAN_005 | Verify logout after login fix | User should logout successfully |

## Regression Testing

Regression testing is performed to ensure that existing functionality is not affected by new changes.

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| REG_001 | Verify login functionality | Login should work correctly |
| REG_002 | Verify dashboard | Dashboard should load correctly |
| REG_003 | Verify user navigation | Navigation should work correctly |
| REG_004 | Verify search functionality | Search results should display correctly |
| REG_005 | Verify logout | User should logout successfully |

## Testing Summary

- Smoke Testing – Build Verification
- Sanity Testing – Change/Bug Fix Verification
- Regression Testing – Existing Functionality Verification
