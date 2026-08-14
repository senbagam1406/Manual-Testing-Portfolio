# API Testing - Postman Test Cases

## API Type
REST API

## Tool
Postman

## API Testing Scenarios

| TC ID | Method | Test Scenario | Expected Result |
|---|---|---|---|
| API_001 | GET | Verify GET request with valid endpoint | Response should be received successfully |
| API_002 | GET | Verify GET request with invalid endpoint | Appropriate 4xx error should be returned |
| API_003 | POST | Create a new record with valid data | Record should be created successfully |
| API_004 | POST | Create record with missing mandatory field | Validation error should be returned |
| API_005 | PUT | Update existing record with valid data | Record should be updated successfully |
| API_006 | PUT | Update non-existing record | Appropriate error response should be returned |
| API_007 | DELETE | Delete an existing record | Record should be deleted successfully |
| API_008 | GET | Verify response status code | Correct HTTP status code should be returned |
| API_009 | GET | Verify response body | Response body should contain expected data |
| API_010 | GET | Verify response time | API should respond within acceptable time |

## HTTP Status Codes

- 200 - OK
- 201 - Created
- 204 - No Content
- 400 - Bad Request
- 401 - Unauthorized
- 403 - Forbidden
- 404 - Not Found
- 500 - Internal Server Error

## Validation Performed

- Request method validation
- URL validation
- Request parameter validation
- Request body validation
- Response status code validation
- Response body validation
- Response time validation
- Positive testing
- Negative testing
