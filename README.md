# Exchange Rate API Testing using Postman

## Project Overview

This project demonstrates API Functional Testing of an Exchange Rate API using **Postman**. The objective is to validate API functionality, response accuracy, data integrity, error handling, and currency conversion through comprehensive  API testing.

This repository showcases my API testing skills using industry-standard QA documentation and Postman collections.

---

## Objectives

- Validate all Exchange Rate API endpoints
- Verify HTTP status codes
- Validate JSON response schema
- Verify exchange rate calculations
- Test historical and latest exchange rate data
- Validate CSV export functionality
- Verify error handling for invalid requests
- Ensure response consistency and reliability

---

## Tools & Technologies

- **Postman**
- REST API
- JSON
- CSV
-  API Testing
- Collection Runner

---

## Project Structure

```
Exchange-Rate-API-Testing/
│
├── README.md
├── Test Plan/
│   └── Exchange Rate API Test Plan.docx
│
├── Test Cases/
│   └── Exchange Rate API Test Cases.xlsx
│
├── Postman Collection/
│   └── Exchange Rate API.postman_collection.json
│
├── Environment/
│   └── Exchange Rate.postman_environment.json
│
├── Test Execution/
│   └── Collection Runner Report.pdf
│
└── Defect Report/
    └── Defect Log.xlsx
```

---

## Test Coverage

The project covers testing of the following API functionalities:

- Latest Exchange Rates
- Base Currency
- Target Currency Filter
- Historical Exchange Rates
- Exchange Rates over Date Range
- Daily Time Series
- Monthly Time Series
- Weekly Time Series
- Provider-wise Exchange Rates
- Attribution Information
- CSV Export
- Currency Information
- Currency Coverage
- Legacy Currencies
- Data Sources
- Single Currency Pair
- Multiple Currency Conversion
- Amount Conversion

---

## Test Scenarios Covered

### Positive Testing

- Valid API requests
- Valid currency codes
- Historical data retrieval
- Time-series data
- Currency conversion
- CSV export
- Provider information

### Negative Testing

- Invalid currency code
- Empty parameters
- Invalid date format
- Future dates
- Invalid group parameter
- Missing mandatory parameters

---

## Validation Performed

- HTTP Status Code Validation
- Response Body Validation
- JSON Schema Validation
- Data Accuracy Validation
- Currency Conversion Validation
- Response Time Validation
- CSV Content Validation
- Error Message Validation

---

## Expected Deliverables

- Test Plan
- Test Scenarios
- Test Cases
- Postman Collection
- Postman Environment
- Collection Runner Report
- Defect Report

---

## Sample Test Cases

| Test Case ID | Scenario | Expected Result |
|--------------|----------|-----------------|
| TC01 | Fetch latest exchange rates | HTTP 200 |
| TC04 | Change base currency | Success |
| TC09 | Filter INR currency | INR returned |
| TC13 | Historical exchange rate | Correct rate |
| TC19 | Exchange rates over period | HTTP 200 |
| TC25 | Daily time series | Daily data returned |
| TC30 | Provider information | Provider returned |
| TC34 | Export CSV | CSV downloaded |
| TC41 | Single currency pair | Accurate exchange rate |

---

## Repository Highlights

- Professional API Test Plan
- Structured Test Cases
- Postman Collection
- Environment Variables
- Collection Runner Execution
- API Validation
- Documentation
- GitHub Portfolio Ready

---

## Skills Demonstrated

- Manual API Testing
- REST API Testing
- Postman
- JSON Validation
- HTTP Methods
- Response Validation
- API Documentation Review
- Test Case Design
- Defect Reporting
- Test Planning
- Functional Testing
- Regression Testing
- Collection Runner
- API Automation Basics

---

## Author

**Deepa Girish Patil**

Software Test Engineer

### Skills

- Manual Testing
- API Testing
- Postman
- Functional Testing
- Regression Testing
- Test Documentation
- Defect Reporting
- GitHub

---

## Future Improvements

- Newman CLI Integration
- Jenkins CI/CD Integration
- Automated API Regression Suite
- HTML Execution Reports
- GitHub Actions Workflow
- Data-driven API Testing

---

## License

This project is created for learning, practice, and professional portfolio purposes.
