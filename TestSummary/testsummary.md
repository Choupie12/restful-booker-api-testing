# Test Summary Report

## Project Name

Restful Booker API Testing

## Test Execution Summary

Total Test Cases Executed: 10

Passed: 8

Failed: 2

## Test Coverage

Tested functionalities:

* Retrieve booking list
* Retrieve booking by ID
* Create booking
* Validate JSON response
* Validate response time
* Negative testing
* Update booking

## Defects Identified

### API_BUG_001

Issue:
PUT endpoint returns HTTP 403 Forbidden despite valid authentication token.

Severity:
Medium

Status:
Open

## Conclusion

The API successfully supports booking retrieval and creation functionalities. Response validation and performance checks were successfully completed. An issue was identified during booking update operations and documented as a defect.

