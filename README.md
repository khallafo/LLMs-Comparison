
LLMs-Comparison
Repository navigation
Code
Issues
Pull requests
LLMs-Comparison
/Project Structure.md
khallafo
khallafo
10 hours ago
129 lines (79 loc) · 2.15 KB

Preview

Code

Blame
LLMs-Comparison
📌Project Scenario
E‑commerce Web Application

Main features:
User registration & login

Product browsing

Add to cart

Checkout & payment

Order history

This scenario covers:
UI testing

API testing

Database validation

Test automation

1️⃣ Requirement Analysis
Sample Requirement

The user can add a product to the cart and check out using a credit card.

#### Llama Prompt
    Analyze this requirement and list:
    - Functional requirements
    - Edge cases
    - Risks
2️⃣ Test Planning
Test Plan Includes

  1. Scope
  
  2. Test types
  
  3. Environment
  
  4. Tools
  
  5. Entry & exit criteria
  
  6. Risks
Llama Prompt
  Generate a professional test plan for an e‑commerce checkout module.
3️⃣ Test Case Design
Example Manual Test Case

Title: Successful checkout with valid Visa card

Steps: 1. Login

2. Add product to cart

3. Open checkout

4. Enter valid card details

5. Confirm payment
Generate Bulk Test Cases with Llama
Create detailed test cases for checkout, including:
- Positive
- Negative
- Boundary
- Security
4️⃣ API Testing
Example Endpoint POST /api/checkout Sample Request { "userId": 10, "items": [{ "id": 5, "qty": 2 }], "paymentMethod": "VISA" }

Llama Prompt
Generate Postman test scenarios and validation scripts for this API.

5️⃣ Automation Testing (UI)
Suggested Stack

Selenium + Java

TestNG

Page Object Model (POM)

Llama Prompt
Write Selenium Java automation for checkout flow using POM and TestNG.

6️⃣ Defect Reporting
Example Bug

Title: Checkout fails with valid MasterCard Severity: Critical

Llama Prompt
Rewrite this bug report in professional excel format.

7️⃣ Test Summary Report
Llama Prompt
Generate a QA test summary report including:

Total executed tests
Passed / Failed
Key defects
Risks
Release recommendation
