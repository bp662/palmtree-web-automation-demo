# PalmTree Web Automation Demo

Welcome to the PalmTree Solutions Web Automation Demo.  
This repository showcases an end-to-end automated testing setup using Cypress, Mochawesome reporting, and a clean, CI/CD-ready architecture.

---

## Tech Stack

- Cypress – Web UI Testing Framework
- Mochawesome – Test Reporting
- CircleCI (optional) – Continuous Integration Pipeline
- GitHub – Source Control and Hosting

---

## Features Tested

- Login Flow
  - Valid and invalid credential scenarios
  - Error message validation
- Add to Cart Flow
  - Adding items to cart
  - Verifying cart contents
- Checkout Flow
  - Filling in customer information
  - Verifying successful order placement

---

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/bp662/palmtree-web-automation-demo.git
   cd palmtree-web-automation-demo

2. npm install - Install dependencies

Note: Cypress is installed locally as a devDependency.  
If you get a "Cannot find module 'cypress'" error, run:

npm install cypress --save-dev

3. npx cypress open - Run Cypress tests

4. npx cypress run - Run tests with Mochawesome reporting

5.	(Optional) View test reports inside /cypress/reports/mochawesome/


## Sample Test Report

Below is a screenshot of a sample Mochawesome report generated after running the Cypress tests:

![Sample Test Report](assets/mochawesome-login-test.png)