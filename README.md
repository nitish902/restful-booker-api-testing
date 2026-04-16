# Restful Booker API Testing with CI/CD (GitHub Actions)

![CI](https://github.com/YOUR_GITHUB_USERNAME/restful-booker-api-testing/actions/workflows/api_test.yml/badge.svg)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange)
![Newman](https://img.shields.io/badge/Newman-CLI%20Runner-blue)
![CI/CD](https://img.shields.io/badge/CI-CD%20Pipeline-green)

---

## Project Overview

This project demonstrates **API testing using Postman** and execution of tests using **CI/CD pipeline with GitHub Actions**.

The Postman collection is executed automatically using **Newman** whenever code changes are pushed to GitHub.

---

## Tools & Technologies

- Postman
- Newman
- GitHub Actions
- REST API
- JSON
- CI/CD

---

## API Under Test

Base URL:https://restful-booker.herokuapp.com/

APIs covered:

1. Get Booking IDs
2. Get Booking Details
3. Create Booking
4. Generate Auth Token

---

## Project Structure

restful-booker-api-testing
│
├── Booking.postman_collection.json
├── README.md
│
└── .github
└── workflows
└── api_test.yml


---

## CI/CD Workflow

CI/CD pipeline automatically runs Postman collection using Newman.

Trigger:
- On push to main branch

Workflow steps:

1. Checkout code from GitHub
2. Install Newman CLI
3. Execute Postman collection
4. Display test results

Workflow file location:.github/workflows/api_test.yml


---

## How to Run Locally

Install Newman:npm install -g newman

Run collection: newman run Booking.postman_collection.json

---

## Import Collection in Postman

1. Open Postman
2. Click Import
3. Select file:

Booking.postman_collection.json

4. Run requests

---

## Learning Outcome

- Understanding REST API testing
- Working with GET and POST requests
- Using Postman collections
- Running tests using Newman
- Implementing CI/CD pipeline
- Automating API testing workflow

---

## Author

Nitish Shukla
