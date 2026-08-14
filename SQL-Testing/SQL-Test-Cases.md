# SQL Testing - Test Cases

## Database Testing

**Database:** SQL Server  
**Tool:** SSMS

## SQL Testing Scenarios

| TC ID | Test Scenario | SQL Validation | Expected Result |
|---|---|---|---|
| SQL_001 | Verify data insertion | Execute INSERT query | Record should be inserted successfully |
| SQL_002 | Verify data update | Execute UPDATE query | Existing record should be updated |
| SQL_003 | Verify data deletion | Execute DELETE query | Record should be deleted successfully |
| SQL_004 | Verify SELECT query | Execute SELECT query | Correct records should be returned |
| SQL_005 | Verify WHERE condition | Execute SELECT with WHERE | Only matching records should be displayed |
| SQL_006 | Verify duplicate records | Check duplicate values | Duplicate records should not exist where restricted |
| SQL_007 | Verify NULL values | Check NULL columns | NULL values should be handled correctly |
| SQL_008 | Verify JOIN results | Execute INNER JOIN | Matching records should be returned |
| SQL_009 | Verify GROUP BY | Execute GROUP BY query | Records should be grouped correctly |
| SQL_010 | Verify data consistency | Compare UI data with DB | UI and database data should match |

## SQL Concepts Covered

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- JOINS
- Subqueries
- NULL Handling
- Aggregate Functions
- Data Validation
- INSERT
- UPDATE
- DELETE

