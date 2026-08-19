# Automation Exercise API Testing

## Overview

This project contains a collection of API tests created in Postman against [Automation Exercise](https://automationexercise.com/), a website designed for practicing software test automation and API testing.

The purpose of this project is to demonstrate practical experience with REST API testing, Postman, request configuration, response validation, and test organization.

## Tools & Technologies

- Postman
- REST API
- JSON
- HTTP methods (GET, POST, PUT, DELETE)
- Git / GitHub

## API Testing Coverage

The collection currently includes tests for several Automation Exercise API endpoints, including:

- Product APIs
- Brand APIs
- Product search
- User account creation
- User authentication
- User account details
- Negative API scenarios
- HTTP status code validation

## Test Scenarios

The collection includes both positive and negative scenarios.

### Positive Testing

Examples include:

- Retrieving products
- Searching for products
- Retrieving user information
- Creating a user account
- Valid requests with required parameters

### Negative Testing

Examples include:

- Missing required parameters
- Invalid requests
- Unsupported HTTP methods
- Invalid user credentials
- Requests using incorrect parameters

## Postman Environment

The collection uses a Postman environment variable:

`base_url`

The environment is configured with:

`https://automationexercise.com`

This allows the API endpoints to use `{{base_url}}` rather than hard-coding the URL into every request.

## How to Run

1. Download or clone this repository.
2. Import `Automation Exercise.postman_collection.json` into Postman.
3. Import `automation_exercise_qa.postman-environment.json`.
4. Select the `automation_exercise_qa` environment in Postman.
5. Open the collection and execute the requests individually or run the collection.

## Project Purpose

This project was created as part of my continued development in QA and test automation. It demonstrates hands-on experience with API testing and complements my experience with manual testing, SQL, Python, and Selenium.

## Future Improvements

Planned improvements include:

- Expanding API test coverage
- Adding additional negative test scenarios
- Adding automated response assertions
- Adding collection-level test execution
- Improving test documentation