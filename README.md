# Software Quality Assurance (SQA) - Manual Testing Project

This repository contains my manual software testing assignment, where I performed functional testing on two web applications and one Android mobile application. The project includes test case design, bug reporting, and documentation of the testing process.

The goal of this project was to practice identifying software defects, writing clear test cases, and documenting test results following standard QA practices.

---

## Applications Tested

### SauceDemo Website
During testing, I verified several core user flows, including:

- Login with different user types (Standard User, Locked Out User, Problem User)
- Adding and removing products from the cart
- Checkout process
- Product display and cart behavior

### DemoQA Website
Testing focused on validating different UI components and user interactions, including:

- Form validation and required fields
- Text box input validation
- JavaScript alert boxes
- Adding, editing, and deleting table records

### My Demo App RN (Android)

For the mobile application, I performed functional and usability testing, including:

- Application installation
- App stability and crash testing
- Product image verification
- Screen rotation
- Offline behavior
- Basic navigation and user interaction

---

## Repository Contents

| File | Description |
|------|-------------|
| **SQA_Manual Testing Assessment_1.pdf** | Complete written assessment with explanations and QA concepts |
| **SQA_Manual_Testing_Assignment1 - Sheet1.xlsx** | Test cases, execution results, bug reports, and testing documentation |

---

## Bugs Identified

### SauceDemo

Some of the issues discovered during testing include:

- Product images are incorrect when logged in as the **Problem User**.
- The cart contains a pre-added item immediately after login.
- The **Remove** button does not work correctly for the preloaded cart item.

### My Demo App RN

The following issues were identified during mobile testing:

- Application crashes on first launch.
- App may crash after remaining idle for several minutes.
- Product images do not update after selecting different color options.
- Screen rotation is not supported.
- Users can continue browsing and adding products while offline without receiving any warning or error message.

---

## Test Cases

This project includes comprehensive manual test cases covering both positive and negative scenarios.

Some of the areas tested include:

- User Login
- Shopping Cart
- Checkout Process
- Form Validation
- Alert Boxes
- Web Tables (Add/Edit/Delete)
- Mobile Installation
- Product Color Selection
- Cart Quantity Validation
- Device Rotation
- Offline Functionality

Each test case contains:

- Test Case ID
- Test Scenario
- Test Steps
- Expected Result
- Actual Result
- Execution Status

---

## Skills Practiced

- Manual Testing
- Functional Testing
- UI Testing
- Positive & Negative Testing
- Test Case Design
- Bug Reporting
- Requirement Validation
- Mobile Application Testing
- Web Application Testing
