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

Continue extending my existing Playwright + TypeScript automation framework.

=========================================================
IMPORTANT
=========================================================

Before generating any code, review the entire existing framework.

Follow all existing Cursor Rules.

Follow the existing framework architecture.

Follow the same coding standards already used for Login and Admin Panel.

Do NOT create a new framework.

Do NOT modify or break any existing working functionality.

Do NOT regenerate Login.

Do NOT regenerate Admin Panel.

Review the entire project before generating any new code.

Search the existing framework for reusable implementations before creating any new file, class or method.

Specifically review and reuse if available:

• BasePage
• Common Helpers
• UI Actions
• Wait Utilities
• Assertion Helpers
• Logger
• JSON Reader
• Environment Configuration
• Existing Page Objects
• Existing Components
• Existing Utilities
• Existing Enums
• Existing Interfaces
• Existing Test Data Structure
• Existing Common Methods

If an implementation already exists, reuse or extend it.

Do NOT duplicate code.

Do NOT duplicate locators.

Do NOT duplicate helper methods.

Do NOT duplicate Playwright actions.

Keep the framework clean, reusable, scalable and production-ready.

Follow

• Page Object Model
• SOLID Principles
• DRY Principle
• Clean Code
• TypeScript Best Practices

=========================================================
TASK
=========================================================

Implement ONLY the Task Creation module.

Do not implement any other module.

=========================================================
PROJECT OPENING
=========================================================

Project navigation is already implemented.

Search the existing framework.

The reusable method

openFirstProjectFromList()

already exists inside

pages/BoardColumnsPage.ts

Reuse this method after successful login.

Do NOT generate another project selection implementation.

Do NOT generate another BoardColumnsPage.

Do NOT create another project navigation helper.

Simply reuse

openFirstProjectFromList()

Flow should be

Login

↓

openFirstProjectFromList()

↓

Verify Project Opened

↓

Continue with Task Creation

=========================================================
TASK CREATION
=========================================================

Task creation supports TWO entry points.

Entry Point 1

Top right

"New Task"

button.

Entry Point 2

"+ Add Task"

button available under every workflow column.

Columns

• Backlog
• Todo
• In Progress
• In Review
• Done

Only popup opening is different.

Once the popup opens,

both entry points must use the SAME reusable implementation.

Do NOT duplicate task creation logic.

=========================================================
TASK CREATION POPUP
=========================================================

Implement the complete Create Task popup.

Fields

• Task Title
• Description
• Column
• Priority
• Due Date
• Assignee
• Attachments
• Depends On Other Tasks
• Create Task
• Cancel

=========================================================
TASK TITLE
=========================================================

Create reusable method

enterTaskTitle()

=========================================================
DESCRIPTION
=========================================================

Create reusable method

enterDescription()

=========================================================
COLUMN
=========================================================

Support

• Backlog
• Todo
• In Progress
• In Review
• Done

Create reusable method

selectColumn(column)

Reuse existing dropdown helper if available.

=========================================================
PRIORITY
=========================================================

Support

• Low
• Medium
• High
• Urgent

Create reusable method

selectPriority(priority)

Reuse existing dropdown helper if available.

=========================================================
DUE DATE
=========================================================

Support BOTH methods.

Method 1

Manual date entry.

Method

enterDueDate()

Method 2

Calendar picker.

Calendar should support

• Today
• Clear
• Previous Month
• Next Month
• Month Dropdown
• Year Dropdown
• Date Selection

Create reusable method

selectDueDateFromCalendar(day, month, year)

Reuse any existing calendar helper if available.

Do NOT duplicate calendar logic.

=========================================================
ASSIGNEE
=========================================================

Assignee list is dynamic.

Implement reusable method

selectAssignee(name)

Reuse existing searchable dropdown implementation if available.

=========================================================
ATTACHMENTS
=========================================================

Support uploading

• PDF
• PNG
• JPG
• JPEG
• GIF
• WEBP
• CSV
• XLS
• XLSX

Implement reusable method

uploadAttachment(filePath)

Use Playwright setInputFiles().

=========================================================
DEPENDS ON OTHER TASKS
=========================================================

This is optional.

Implement reusable methods

searchDependentTask(taskName)

selectDependentTask(taskName)

Reuse existing searchable dropdown helper if available.

=========================================================
CREATE TASK
=========================================================

Create ONE reusable method

createTask(taskData)

Do NOT pass individual parameters.

Create a TaskData interface.

Read all test data from

taskData.json

TaskData should contain

• title
• description
• column
• priority
• dueDate
• assignee
• attachment
• dependsOnTask
• entryMethod

=========================================================
VERIFICATION
=========================================================

After clicking Create Task

Verify

• Success Toast Message
• Task Card Created Successfully
• Task Title
• Column
• Priority
• Assignee
• Due Date

=========================================================
TEST DATA
=========================================================

Create

taskData.json

Include

Positive Test Data

Minimal Required Data

Different Priorities

Different Columns

Attachment Data

Dependency Data

=========================================================
FRAMEWORK EXPECTATIONS
=========================================================

Before creating any new helper or class,

search the existing framework first.

If an implementation already exists,

reuse it.

Only create new code when absolutely necessary.

Keep methods small.

Keep page objects clean.

Do NOT keep assertions inside page objects.

Assertions should remain inside test files.

Follow existing project folder structure.

Follow existing naming conventions.

Preserve backward compatibility.

Do NOT modify Login.

Do NOT modify Admin Panel.

=========================================================
EXPECTED OUTPUT
=========================================================

1. Review the existing framework.

2. Explain what existing classes and methods will be reused.

3. Explain whether any new helper is actually required.

4. Generate only the new files required for Task Creation.

5. Reuse openFirstProjectFromList() from BoardColumnsPage.ts.

6. Generate TaskModal page object.

7. Generate TaskData interface.

8. Generate taskData.json.

9. Generate task-creation.spec.ts.

10. Review the generated code and remove any duplicate logic before completing the response.

Generate enterprise-level production-ready code following the existing framework without breaking any current implementation.
