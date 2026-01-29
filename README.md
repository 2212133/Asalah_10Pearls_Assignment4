# Asalah's Assignment No. 4 – API Testing with Postman

## Project Overview
This repository contains a Postman collection and environment for testing the **Restful-API.dev**. It demonstrates proficiency in multiple HTTP methods, variable handling, and API chaining.

## Tasks Completed
- **Task 1:** Used GET, POST, PUT, PATCH, and DELETE methods.
- **Task 2:** Configured `baseUrl` as an environment variable.
- **Task 3:** Integrated dynamic variables like `{{$randomFullName}}` for random request data.
- **Task 4:** Parsed JSON responses and logged IDs to the Postman Console.
- **Task 5:** Wrote Chai assertions, including a deliberate failing test case for verification.
- **Task 6:** Utilized **Pre-request** and **Post-response** (Tests) sections for variable logic.
- **Task 7:** Implemented API chaining by saving the `objectId` from a POST response to use in subsequent requests.

## How to Run
1. **Import the Collection:** Download the `.json` file and import it into Postman.
2. **Open Console:** View logs in the Postman Console (`Ctrl + Alt + C`).
3. **Run:** Execute the requests in order (POST -> GET -> PUT/PATCH -> DELETE).
