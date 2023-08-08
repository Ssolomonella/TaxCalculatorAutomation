# INDEX
- [PROJECT DESCRIPTION](#project-description)
- [TEST APPROACH](#test-approach)
  - [Test Levels](#test-levels)
    - [Unit Testing](#unit-testing)
    - [Integration Testing](#integration-testing)
    - [System Testing](#system-testing)
    - [Acceptance Testing](#acceptance-testing)
  - [Test Types](#test-types)
    - [Black Box](#black-box)
      - [Functional Testing](#functional-testing)
      - [Non-Functional Testing](#non-functional-testing)
    - [White Box](#white-box)
- [TEST MANAGEMENT](#test-management)
  - [JIRA](#jira)
    - [Zephyr Scale](#zephyr-scale)
  - [Test Plans](#test-plans)
    - [Sprint 1](#sprint-1)
    - [Sprint 2](#sprint-2)
    - [Sprint 3](#sprint-3)
      - [Test Artifacts](#test-artifacts)
- [AGILE METRICS](#agilescrum-metrics)
- [DEFECT MANAGEMENT](#defect-management)
- [TEST EXIT REPORT](#test-exit-report)
# PROJECT DESCRIPTION

---
The project involved the creation of a comprehensive Tax Calculator App designed to automate the calculation of income tax based on user input and subsequently determine the tax bracket applicable to the user. The development process was broken down into several phases, each with its own specific testing procedures.

# Test Approach

---

## Test Levels
### Unit Testing
In the initial phase, we worked on the unit testing. Each function or method built to perform specific calculations was thoroughly tested in isolation. For example, a function designed to calculate the tax amount based on the tax rate and taxable income was unit tested to ensure it provided accurate results for different combinations of inputs.
### Integration Testing
During the integration testing phase, the app's various components, like the income input module, tax bracket determination module, and tax calculation module, were tested together to ensure they interacted properly. We checked for accurate data flow between these modules and verified the correct results were produced when they were combined.
### System Testing
Following integration testing, system testing was performed. This phase involved testing the entire system in an environment that closely mimicked the real-world scenario. We ensured the app functioned as intended, verifying the calculations of income tax, the correct determination of the tax bracket, and overall application performance.
### Acceptance Testing
Finally, we conducted acceptance testing to confirm the app met user requirements and provided a satisfactory user experience. We simulated a user's interaction with the app, inputting income details, and checking the output, the tax calculation, and tax bracket determination.

Each testing phase was instrumental in catching defects early and ensuring the integrity of the app. My role was to lead and participate in these testing activities, utilizing my software testing skills to ensure the app was reliable, robust, and user-friendly.
## Test Types
### Black Box
#### Functional Testing
![Tax Calculator API Lower and Upper Boundary Testing](/Assets/Tax%20Calc%20lower%20and%20upper%20boundaries.png)
![Tax Calculator API Within Boundary Testing](/Assets/Tax%20Calc%20within.png)
![Tax Calculator API GET Income Bracket](/Assets/Tax%20Calc%20GET%20brackets.png)

#### Non-Functional Testing
![Tax Calculator Performance Testing](/Assets/Tax%20Calc%20Performance.png)
![Tax Calculator Accessibility Testing](/Assets/Tax%20Calc%20Acc.png)
![Tax Calculator Accessibility Testing](/Assets/Tax%20Calc%20Acc2.png)
![Tax Calculator Accessibility Testing](/Assets/Tax%20Calc%20Acc3.png)


### White Box

# Test Management

---
## Jira
### Zephyr Scale

[UI Component Test Suite](https://techdojob2.atlassian.net/projects/ST?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCases?projectId=10002)

## Test Plans
### Sprint 1
![Test Plan Sprint 1](/Assets/UI%20Test%20Plan%201.png)
### Sprint 2
![Test Plan Sprint 2](/Assets/API%20testing%20Test%20plan.png)
### SPrint 3
![Test Plan Sprint 3](/Assets/API%20system%20testing%20test%20plan.png)
#### Test Artifacts
[UI Component Test Suite](https://techdojob2.atlassian.net/projects/ST?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCases?projectId=10002)

[**Income Tax Calculator** UI Analysis and Design](https://onedrive.live.com/edit.aspx?resid=2D6E5952BC1F4D27!19121&ithint=file%2cdocx&ct=1690190796276&wdOrigin=OFFICECOM-WEB.START.EDGEWORTH&wdPreviousSessionSrc=HarmonyWeb&wdPreviousSession=63196499-6aed-431c-b1a9-69c6f71a262a)


# Agile/Scrum Metrics

---
![Burndown Chart](/Assets/IH_Dynamic_Status_Update_2023-07-24_21_33.png)
![Burndown Chart](/Assets/IH_Dynamic_Status_Update_2023-07-24_21_34.png)

# Defect Management

---
![Jira Report](/Assets/Jira%20Defect.png)
![Postman Screenshot](/Assets/Postman%20defect.png)
# Test Exit Report

---
## Tax Calculator API UI- Test Progress Report

Test Execution Summary:

The Tax Calculator API has undergone thorough testing, with a total of 32 test cases executed across different components. All tests were executed successfully, and no defects were found during the test execution phase.

Here's the breakdown:

API UI Component:

Total Test Cases: 32

Passed: 32

Failed: 0

Button Component:

Total Test Cases: 9

Passed: 9

Failed: 0

Summary Area Component:

Total Test Cases: 8

Passed: 8

Failed: 0

Input Field Component:

Total Test Cases: 8

Passed: 8

Failed: 0

Alert Message Component:

Total Test Cases: 7

Passed: 7

Failed: 0

Test Case Pass Percentage:

API UI Component: 100% (32/32 x 100)

Button Component: 100% (9/9 x 100)

Summary Area Component: 100% (8/8 x 100)

Input Field Component: 100% (8/8 x 100)

Alert Message Component: 100% (7/7 x 100)

Conclusion:

The test execution for the Tax Calculator API has been comprehensive and successful. All the executed test cases for the API UI, Button Component, Summary Area Component, Input Field Component, and Alert Message Component have passed, resulting in a 100% pass rate across the board. The testing phase ensures that the system is functioning as expected, and the Tax Calculator API is ready for deployment.





## Test Progress Report for Tax Calculator API  – SH Team

1. Executive Summary

This report provides a summary of the testing activities and results for the Tax Calculator API. During the reporting period, we executed 27 test cases focusing on three endpoints: Retrieval of Tax Brackets, Finding Tax Brackets, and Tax Calculation.

Overall, the API demonstrated a high degree of conformance with the specifications, with all but one of the test cases passing. This indicates that the API is mostly working as expected and users are likely to have a positive experience.

2. Test Execution Summary

Out of the 27 test cases executed, 26 passed, and 1 failed. The details are as follows:

Retrieval of Tax Brackets: 1/1 passed

Finding Tax Brackets: 7/8 passed, 1 failed

Tax Calculation: 18/18 passed

3. Defects

We found one defect during the test execution in the Finding Tax Brackets functionality:

Negative Numerical Input Accepted by the Find Tax Bracket Endpoints

Defect Description: Negative numerical input accepted by the Find Tax Bracket endpoint

Status: Unresolved

This defect allows users to input negative numbers which is not a valid scenario for tax bracket calculation.

4. Progress Indicators









Total test cases planned: 27

Total test cases executed: 27

Total test cases passed: 26

Total test cases failed: 1

Defects opened: 1

Defects resolved: 1

5. Conclusions and Recommendations

The overall quality of the Tax Calculator API is high, with a pass rate of 96.4%. However, there is one defect that needs to be addressed to ensure that users cannot input negative numbers for tax calculation.

Our recommendation is to focus efforts on resolving this defect before final release. Once this defect has been resolved, we will need to re-run the test cases to confirm that the issue has been adequately addressed.

We look forward to your feedback on this report and any further directions you might have for our testing efforts.



Addendum:

The defect has now been resolved and the Tax Calculator API has now a 100% pass rate.  
