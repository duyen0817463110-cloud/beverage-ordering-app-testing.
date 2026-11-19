# Beverage Ordering Application – Manual Testing & Defect Management

## 1. Project Overview

This project focuses on manual testing and defect management for a Beverage Ordering Mobile Application.

The main objective is to evaluate the application's functional correctness, identify defects, verify expected system behaviors, and propose improvements to enhance user experience and application quality.

The project covers customer and administrator workflows, including account management, beverage selection, shopping cart operations, payment processes, and revenue management.

## 2. Testing Scope

The testing activities cover the following functional modules:

| Module | Description |
|---|---|
| UC1 | User Registration |
| UC2 | User Login |
| UC3 | User Logout |
| UC4 | Password Recovery |
| UC5 | Change Password |
| UC6 | Beverage Selection and Add to Cart |
| UC7 | View and Edit Shopping Cart |
| UC8 | Payment Process |
| UC9 | Add and Delete Beverages (Admin) |
| UC10 | View Invoices and Revenue Statistics |

Additional testing activities:
- Permission Matrix validation for different user roles.
- Positive and negative test scenarios.
- Input validation and error message verification.
- Functional behavior verification.
- Defect identification and documentation.

## 3. Testing Documentation

The project includes the following testing deliverables:

**Test Cases**
- Designed test cases for 10 functional modules (UC1–UC10).
- Defined preconditions, test procedures, expected results, and actual results.
- Covered positive and negative testing scenarios.

**Test Execution Report**
- Recorded test execution results.
- Summarized Pass, Fail, Not Tested, and Not Applicable cases.
- Evaluated test coverage and successful execution coverage.

**Permission Matrix**
- Documented access permissions across different user roles.
- Reviewed functional access restrictions.

**Defect Log**
- Recorded identified defects.
- Documented affected functions, reproduction steps, and defect descriptions.

## 4. Test Execution Summary

According to the recorded Test Report:

| Metric | Result |
|---|---:|
| Total Test Cases | 47 |
| Passed | 21 |
| Failed | 4 |
| Not Tested | 2 |
| Not Applicable | 24 |
| Test Coverage | 53.19% |
| Successful Coverage | 84% |

**Note:** Some administrator and payment-related test cases were marked Not Applicable because the corresponding functionalities or administrator account were not yet available in the application.

## 5. Defect Management

The project identified and documented functional issues, including:

| Module | Identified Defect |
|---|---|
| Password Recovery | Incorrect notification displayed after entering a valid email address. |
| Password Recovery | Incorrect notification displayed after entering a valid phone number. |
| Shopping Cart | Beverages with zero available quantity could still be added to the cart. |
| Shopping Cart | Items remained in the cart when their quantity was reduced to zero. |

Defect documentation includes:
- Affected functionality.
- Defect title and description.
- Reproduction steps.
- Recorded defect date.
- Corrective action documentation field.

## 6. Jira – Backlog & Sprint Board

Jira was used to organize project tasks and track their progress.

The project backlog included improvement tasks such as:
- Adding Gmail and phone number fields for password recovery.
- Implementing a password visibility toggle.
- Integrating a multi-bank payment gateway.
- Supporting multiple languages (English and Vietnamese).
- Tracking a password visibility defect.

The Jira board provides visibility into task progress through workflow statuses such as To Do, In Progress, and In Review.

### Jira Backlog

![Jira Backlog](Jira-Evidence/Jira_Backlog.png)

### Jira Sprint Board

![Jira Sprint Board](Jira-Evidence/Jira_Sprint_Board.png)

## 7. Improvement Proposals

Based on the testing observations, the following improvements were proposed:

- Add Gmail and phone number fields during registration to support password recovery.
- Implement a password visibility toggle on the login screen.
- Integrate bank payment methods to improve payment convenience.
- Support multiple languages, including English and Vietnamese.

These improvements aim to enhance usability, accessibility, and overall application experience.

## 8. Tools & Technologies

- **Testing Approach:** Manual Testing
- **Test Documentation:** Microsoft Excel, Microsoft Word
- **Project & Defect Management:** Jira
- **Browsers:** Google Chrome, Microsoft Edge

## 9. Key Learning Outcomes

Through this project, I gained practical experience in:

- Analyzing functional requirements and identifying test scenarios.
- Designing and executing manual test cases.
- Performing positive and negative testing.
- Preparing test execution reports and permission matrices.
- Identifying, documenting, and tracking software defects.
- Using Jira to manage project tasks and monitor workflow progress.
- Analyzing application limitations and proposing improvements.

---

**Project Type:** Academic Project  
**Role:** Manual Tester  
**Focus:** Functional Testing, Test Case Design, Test Execution, Defect Reporting, and Jira
