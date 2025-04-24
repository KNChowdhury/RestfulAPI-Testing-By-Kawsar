# RestfulAPI Testing by Kawsar Newaz Chowdhury

Welcome to the **RestfulAPI Testing** repository! This repository contains API tests for a booking system built with **Postman** and **Newman**. The collection and environment files are designed to test various API endpoints for booking and retrieving booking information, validating schemas, and ensuring the API is functioning correctly and efficiently.

## Features:
- **Create Booking**: Send a POST request to create a new booking.
- **Get Booking Info**: Retrieve the details of a specific booking.
- **Assertions**: Test includes schema validation, response time checks, content type validation, and response status verification.
- **HTML Report**: Comprehensive test results in an easy-to-read HTML format.

## Project Structure:
The project consists of the following files:
- **Postman Collection**: Contains the API requests and tests.
  - `RestfulAPI.postman_collection.json`
- **Postman Environment**: Stores environment variables, such as the `Base_url` and other dynamic values.
  - `RestfulAPI.postman_environment.json`
- **Newman HTML Report**: Generated after executing the tests via Newman.
  - `RestfulAPI-2025-04-24-17-28-36-928-0.html` (This report includes detailed execution results).

## Prerequisites:
To run the API tests, you need the following:
- **Postman**: To create, test, and debug API requests.
- **Newman**: Command-line tool for running Postman collections.
- **Node.js**: Required for installing **Newman** via **npm**.
- **npm**: Node.js package manager to install dependencies.

### Install Node.js and Newman
1. Install **Node.js** from [here](https://nodejs.org/).
2. Once Node.js is installed, run the following command to install **Newman** globally:
   ```bash
   npm install -g newman
