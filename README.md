# E-Commerce API Test Project

## Overview
Postman-based API test suite for the E-Commerce REST API.
Base URL: https://jsonplaceholder.typicode.com

## Test Coverage
- 15 test cases: Smoke, Regression, Negative, Schema, Performance
- Tools: Postman, Newman CLI

## How to Run
1. Import `E-Commerce-API-Tests.postman_collection.json` into Postman
2. Import `Dev.postman_environment.json` as environment
3. Run via Collection Runner or Newman:

```
newman run E-Commerce-API-Tests.postman_collection.json \
  -e Dev.postman_environment.json -r htmlextra
```

## Author
Divya — QA Engineer
