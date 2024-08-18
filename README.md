# Technical-testing-task

# Execution Using Postman

### Prerequisites
- Ensure you have Postman installed on your machine. 
- Access to the Swagger Petstore API documentation: [Swagger Petstore](https://petstore.swagger.io/).
•	Access the Swagger Petstore API Documentation:
o	URL: https://petstore.swagger.io/

 **Test Scenarios for CRUD Operations**
1 Create (POST)
•	Scenario 1: Successfully create a pet with valid inputs.
•	Scenario 2: Attempt to create a pet with missing required fields.
•	Scenario 3: Test creating a pet with duplicate ID.
•	Scenario 4: Test creating a pet with special characters in the name.
2. Read (GET)
•	Scenario 1: Successfully retrieve pet details using a valid ID.
•	Scenario 2: Attempt to retrieve details of a pet that does not exist.
•	Scenario 3: Successfully retrieve pet details By Status 
•	Scenario 4: Successfully retrieve pet details By Tag
3. Update (PUT)
•	Scenario 1: Successfully update existing pet details 
•	Scenario 2: Attempt to update a pet that does not exist.
•	Scenario 3: Attempt to update a pet with invalid data types.
4. Delete (DELETE)
•	Scenario 1: Successfully delete a pet using a valid ID.
•	Scenario 2: Attempt to delete a pet that does not exist.
•	Scenario 3: Verify the response when attempting to delete a pet with an invalid ID.

 **Execution of Test Cases**
 Executing test case by click on send button for each request and verify the response code 
 **Collection Runner**:
 We can  Use Postman’s Collection Runner to execute multiple test scenarios in sequence.
** Reporting **:
After executing the test scenarios, you can export the collection and the results in JSON or HTML format.

"Version Control"
Upload your results in the github and update the readme File with any changes and test execution 
