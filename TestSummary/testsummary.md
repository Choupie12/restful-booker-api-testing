# Test Summary Report

## Project Name

Restful Booker API Testing

## Test Execution Summary

Total Test Cases Executed: 11

Passed: 9

Failed: 2

## Test Coverage

Tested functionalities:

* Retrieve booking list
* Retrieve booking by ID
* Create booking
* Update booking
* Validate JSON response
* Validate response time
* Negative testing
* Update booking

## Defects Identified

### API_TC_009

Issue:
Send POST request with incomplete JSON body returns HTTP 500  Internal Server Error.

Severity:
Medium

Status:
Open

### API_TC_011

Issue:
PUT endpoint returns HTTP 403 Forbidden despite valid authentication token.

Severity:
Medium

Status:
Open

## Conclusion

The API successfully supports booking retrieval and creation functionalities. Response validation and performance checks were successfully completed. Two issues were identified and documented as a defect.

