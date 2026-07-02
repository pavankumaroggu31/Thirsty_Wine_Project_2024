# Thirsty Wine Website Testing
## Project Title : Thirsty Wine

## Introduction :
  The Thirsty Wine website is an e-commerce platform where users can    browse, search, purchase, and review various wines. The website also offers features like user registration, login, order management, payment processing, and customer support. This test plan outlines the manual testing strategy to verify that all core functionalities work as expected, are user-friendly, and perform efficiently across different devices and browsers.

## Project Type :
  Frontend Manual Testing – This project involves manual testing of the frontend of the Thirsty Wine website. The testing will focus on verifying the functionality, usability, and compatibility of the site across different browsers and devices.

## Deployed App :
The deployed application can be accessed at:
https://pay-pal-pioneers-068.vercel.app/

## Test Plan :
The Test Plan describes how we will test the Thirsty Wine website, what features will be tested, and the timeline for testing. It outlines the goals, approach, and schedule for ensuring the website works well and is secure. You can find the full Test Plan document [here](<https://docs.google.com/document/d/1WxQhFqUXna3tx6VtxouM0g9-v3kacCM5cG6HChtYZOM/edit?usp=sharing>)

## Test Scenarios :
The test scenarios cover various aspects of the Thirsty Wine website, ensuring that key features like user registration, login, and password recovery work as expected. These scenarios guide the testing process to validate both functionality and usability.
You can view the detailed test scenarios [here](<https://docs.google.com/spreadsheets/d/1_My8rBnCUh2UbHPr5FDTUNRpugGyfCK1/edit?usp=sharing&ouid=110433349378414708907&rtpof=true&sd=true>)

## Test Cases :
The test cases cover both functional and usability testing for key features such as Forgot Password, Login, and Registration. These test cases ensure that the website works correctly and is easy to use for all users.
You can view the detailed test cases [here](<https://docs.google.com/spreadsheets/d/11DXNosLJbXA4p_Pbn0GNsLLeHAlaSU8i/edit?usp=sharing&ouid=110433349378414708907&rtpof=true&sd=true>)

## Bug Reports :
During testing, defects were logged with detailed information, including steps to reproduce the issue and its severity. This helps track and resolve problems efficiently.
You can find the full bug report [here](<https://docs.google.com/spreadsheets/d/1I3BFk2jcgnKkmbG65urGS1jD0z7Ln5q3/edit?usp=sharing&ouid=110433349378414708907&rtpof=true&sd=true>).

## Test Summary Report :
The test summary report gives an overview of the testing process, including what was tested, the results, and any issues found. It helps to understand the overall quality of the Thirsty Wine website.
You can view the detailed test summary report [here](<https://drive.google.com/file/d/19m0JizVhzZXs3wdgZNx8QvWqsseh2dxg/view?usp=sharing>).

## Mind Map :
The mind map provides a visual overview of the testing process, showing how different features and test scenarios are connected. It helps to understand the structure of the testing plan and guide the testing efforts.
You can view the detailed mind map [here](<https://drive.google.com/file/d/1LsI6XLTKE6xJEvBw9PsOF3UC6eNOcVUE/view?usp=sharing>).

## Video Walkthrough of the project
This is my video of the project presentation [here](<https://youtu.be/sjtR9o0qGDU>)


## Features

1.User Registration & Login

2.Product Browsing & Search

3.Shopping Cart

4.Checkout Process
 

5.Payment Gateway

6.Order Management

7.User Reviews & Ratings

8.Cross-Browser Compatibility

9.Security Features

10.Refunds/Returns

11.Notifications

## Usage
How to Use the Project for Testing

Access the Website: Visit the website at https://pay-pal-pioneers-068.vercel.app/

Test Key Features: Go through the core functionalities (registration, login, cart, checkout) and verify if they work as expected.

Cross-Browser Testing: Open the website on different browsers (Chrome, Firefox, Safari) and check if it works well.

Report Bugs: If you encounter any issues, follow the bug report format below.

## Credentials
For testing purposes, use the following test accounts:

Test User 1

Username: pavankumar@gmail.com

Password: 123456

Test User 2

Username: gurusmaran@gmail.com

Password: 123456

## Technology Stack
The Thirsty Wine website is built using the following technologies:

Testing Tools:

Google Sheets – For documenting test cases and logging defects.

Google docs

Xmind Map

Google Drive

ICE POT Prompt

I – Instruction

Generate a complete, production-ready automation framework for the
Login functionality using Playwright with TypeScript. Implement the
framework using the Page Object Model (POM) design pattern and follow
industry-standard coding practices. The code should be modular,
reusable, maintainable, and scalable with proper assertions, error
handling, logging, and explicit waits.


C – Context

Application Details:

Application URL: https://taskflow-prod.netlify.app/dashboard

Login Credentials

Email: shubham.kumar@braincellinfotech.ai
Password: Braincell@999

Automation Flow:

Launch the browser.
Navigate to the application.
Verify the Login page is displayed.
Enter the email address.
Enter the password.
Click the Login button.
Verify successful login by validating the Dashboard or another unique
post-login element.
Capture screenshots on failure.
Close the browser after test execution.

Framework Requirements:

Playwright with TypeScript
Page Object Model (POM)
Separate Page Classes
Test Data Management
Configuration Management
Environment Support
Reusable utility methods
Meaningful assertions
Proper waits (avoid hard-coded waits)
Scalable folder structure


E – Example

Expected Project Structure

playwright-framework/

│

├── pages/

│   └── LoginPage.ts

│

├── tests/

│   └── login.spec.ts

│

├── fixtures/

│   └── testData.ts

│

├── utils/

│   ├── constants.ts

│   └── helper.ts

│

├── playwright.config.ts

├── package.json

├── tsconfig.json

└── README.md

Example Page Object Methods

navigate()


enterEmail(email: string)


enterPassword(password: string)


clickLogin()


verifySuccessfulLogin()

Example Test Flow

Login Test


→ Launch Browser


→ Navigate to Application


→ Login using valid credentials


→ Verify Dashboard


→ Capture Screenshot on Failure


→ Close Browser


P – Persona

Act as a Senior Playwright Automation Architect with 10+ years of
experience in building enterprise-grade automation frameworks using
Playwright and TypeScript.

Follow industry best practices including:

Page Object Model (POM)
SOLID Principles
DRY (Don't Repeat Yourself)
Clean Code Architecture
Reusable Components
TypeScript Best Practices
Explicit Wait Strategies
Robust Assertions
Centralized Locators
Configuration-driven Framework
Environment Variable Support
Proper Error Handling
Logging and Reporting Ready Structure
Easy Integration with CI/CD pipelines (GitHub Actions, Azure DevOps, Jenkins)

Write code that is clean, scalable, production-ready, and easy to maintain.


O – Output Format

Generate the response in the following order:

Project Folder Structure
Prerequisites
Required Dependencies
Installation Commands
Playwright Configuration (playwright.config.ts)
TypeScript Configuration (tsconfig.json)
Test Data File
Utility Files
Login Page Object (LoginPage.ts)
Login Test (login.spec.ts)
Explanation of Each File
Commands to Execute the Tests
Expected Test Execution Output
Framework Best Practices Followed
Suggestions for Future Enhancements

Use separate Markdown code blocks for each file with the appropriate
language syntax highlighting (typescript, json, bash, etc.).


T – Task

Build a complete Playwright automation framework in TypeScript to
automate the Login functionality of the provided application using the
Page Object Model (POM).

The framework should:

Be executable with minimal setup.
Follow enterprise-level automation standards.
Use reusable page objects.
Include meaningful assertions.
Handle failures gracefully.
Support future scalability.
Be easy to extend for additional test cases.
Follow Playwright and TypeScript best practices throughout the implementation.
