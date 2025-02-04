# Project-3

# Sprint 4: APIs

# Project 4: Task
For this project, you'll need to use API documentation to access all the information about the endpoints you will test — please use apiDoc, which can be accessed at URL + /docs/.

# Task description
1. Analyze these two requirements: “Working with kits” and  “Working with deliveries”. 
2. Design tests cases to cover the features you received for testing.
3. Run your test cases through Postman and create bug reports in Jira for any bugs you find.
4. Write a test report. What can you tell the team about the status of the part of the product you tested? 


# Requirements to be tested

💻 Requirement 1: Working with kits

The user should be able to add existing products to a kit using the endpoint POST URL + /api/v1/kits/:id/products unless the number of products in the kit exceeds the limit of 30. 

When adding non-existent product IDs, 400 Bad Request should be returned. 

When adding products to a non-existing kit ID, 404 Not Found should be returned. 

In cases when the request body does not contain the right structure, 400 Bad Request should be returned.

💻 Requirement 2: Working with deliveries

The “Fast Delivery” service should be available if the Shipping Price Calculation Requirements are met. 

The endpoint is /fast-delivery/v3.1.1/calculate-delivery.xml. See the “Couriers” part of apiDoc for information about the request structure.



