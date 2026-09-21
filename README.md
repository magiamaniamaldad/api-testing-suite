# 🧪 API Testing Suite

Automated REST API testing project built with **Postman** and **Newman**, focused on validating API behavior, response data, status codes, and error handling.

The test suite can be executed automatically through **GitHub Actions** on every push or pull request.

## 🔎 What It Tests

The suite demonstrates automated validation of REST API endpoints, including:

- HTTP status code validation
- Response body validation
- JSON data checks
- Expected API behavior
- Error response handling
- Automated regression testing

## 🛠️ Tech Stack

- Postman
- Newman
- JavaScript
- Node.js
- GitHub Actions
- REST APIs
- JSON

## 📁 Project Structure

```text
api-testing-suite/
├── .github/
│   └── workflows/
│       └── api-tests.yml
├── postman/
│   └── API-Testing-Suite.postman_collection.json
├── package.json
└── README.md

```

## ⚙️ Running the Tests

Install the project dependencies:

```bash
npm install
```

Run the API test suite:

```bash
npm test
```

Newman executes the Postman collection from the command line and reports the results of each API request and assertion.

## 🔄 Continuous Integration

GitHub Actions automatically runs the API test suite when changes are pushed to the `main` branch or submitted through a pull request.

The CI pipeline:

1. Checks out the repository
2. Sets up Node.js
3. Installs project dependencies
4. Executes the Postman collection with Newman
5. Reports whether the automated API tests passed or failed

## 🎯 Project Purpose

This project demonstrates practical API QA skills by combining REST API validation, automated assertions, command-line test execution, and continuous integration.

It complements my UI automation and backend data validation projects by focusing specifically on **API-level quality assurance**.
