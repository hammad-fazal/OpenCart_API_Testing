# OpenCart API Testing Project (Postman)

## Overview

This project demonstrates API testing of the OpenCart e-commerce platform using Postman. The collection validates core shopping cart functionalities through automated API requests, test scripts, and assertions.

The project follows an end-to-end customer workflow, starting from API authentication and continuing through cart operations such as adding, retrieving, updating, and removing products.

---

## Objectives

* Validate OpenCart REST API functionality
* Automate API testing using Postman
* Verify API responses through automated assertions
* Generate execution reports using Newman

---

## Tested APIs

### 1. Create Session / API Token

**Method:** POST

**Purpose:**

* Authenticate with OpenCart API
* Generate an API token for subsequent requests

**Validations:**

* Status code is 200
* Success message is returned

---

### 2. Add Product to Cart

**Method:** POST

**Purpose:**

* Add a product to the shopping cart

**Validations:**

* Status code is 200
* Product addition success message is returned

---

### 3. Get Cart Contents

**Method:** GET

**Purpose:**

* Retrieve products currently present in the cart

**Validations:**

* Status code is 200
* Cart ID is present in the response

---

### 4. Edit Product Quantity

**Method:** POST

**Purpose:**

* Update product quantity in the cart

**Validations:**

* Status code is 200
* Success response is returned

---

### 5. Remove Product from Cart

**Method:** POST

**Purpose:**

* Remove product from the cart

**Validations:**

* Status code is 200
* Product removal success message is returned

---

## Test Execution Summary

| Metric                | Result |
| --------------------- | ------ |
| Total Requests        | 5      |
| Test Scripts          | 10     |
| Assertions            | 10     |
| Failed Tests          | 0      |
| Success Rate          | 100%   |
| Average Response Time | 74 ms  |

### Execution Result

✅ All API requests executed successfully

✅ All assertions passed

✅ No failures detected

---

## Tools & Technologies

* Postman
* Newman
* JavaScript (Postman Test Scripts)
* REST API Testing
* JSON
* Git & GitHub

---

## Key Features

* Automated API validation
* Dynamic API token handling
* Request chaining
* Response verification
* Cart workflow testing
* Newman HTML reporting
* CI/CD ready collection structure

---

## Project Structure

```text
OpenCart-API-Testing/
│
├── OpenCart_API_Collection.json
├── Environment.json
├── Newman_Report.html
├── README.md
```

---

## How to Run

### Run in Postman

1. Import the collection.
2. Import the environment file.
3. Execute the collection using Collection Runner.

### Run with Newman

```bash
newman run OpenCart_API_Collection.json \
-e Environment.json \
-r cli,html
```

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* API testing fundamentals
* REST API validation
* Postman scripting
* Test automation
* Request parameterization
* API authentication workflows
* Newman reporting
* GitHub project documentation

---

## Author

**Hammad Fazal**

Telecommunications Engineer | Production Analyst | Aspiring QA & DevOps Engineer

GitHub: [Add Your GitHub Profile Link]
LinkedIn: [Add Your LinkedIn Profile Link]
