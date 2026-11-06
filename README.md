# Amazon Mobile Application – Manual Testing Project

## 📌 Project Overview

This project focuses on manual testing of the Amazon Android mobile application to evaluate its functionality, usability, and compatibility.

Testing was performed manually on a real Android device. Test cases were designed to verify positive scenarios, negative scenarios, and basic edge cases across important application modules.

## 🎯 Project Objectives

- Understand and practise the manual testing process.
- Design and execute test cases for mobile application functionalities.
- Validate application behaviour using positive and negative test scenarios.
- Identify, document, and report application defects.
- Prepare test execution reports and test summaries.

## 📱 Application Details

| Item | Details |
|---|---|
| Application | Amazon |
| App Version | 32.18.0.300 |
| Platform | Android |
| Device | POCO M4 5G |
| Android Version | 14 |
| Testing Type | Manual Testing |
| Testing Period | 02/11/2026 – 05/11/2026 |
| Tester | Sai Sangeetha Padakanti |

## 🔍 Testing Scope

The following modules were covered:

### 1. Login Testing
- Valid mobile number and correct OTP
- Incorrect OTP
- Empty mobile number
- Invalid mobile number

### 2. Search Testing
- Valid product search
- Invalid search input
- Empty search
- Special characters and irrelevant search results

### 3. Cart Testing
- Adding products to cart
- Increasing and decreasing product quantity
- Removing items from cart

### 4. Checkout Testing
- Invalid coupon code
- Back navigation during checkout

### 5. Usability Testing
- Screen rotation
- Layout and data consistency

### 6. Compatibility Testing
- Internet disconnection
- Incoming call interruption

## 🧪 Testing Approach

- Manual black-box testing on a real Android device.
- Positive and negative test case execution.
- Validation of actual results against expected results.
- Basic UI and usability checks.
- Documentation of test execution results.
- Defect reporting with reproduction steps, severity, priority, and screenshot evidence.

## 📊 Test Execution Summary

| Metric | Count |
|---|---:|
| Total Test Cases | 15 |
| Passed | 14 |
| Failed | 1 |
| Defects Identified | 1 |

**Test Result:** One defect was identified in the Search module. The application displayed irrelevant search results when special characters (`@#$%^`) were entered instead of displaying an appropriate no-results message.

*Results reflect only the selected test scenarios executed in the specified test environment.*

## 🐞 Defect Report

| Item | Details |
|---|---|
| Bug ID | BUG-001 |
| Module | Search |
| Related Test Case | TC06 |
| Defect Title | Irrelevant search results displayed for special character input |
| Severity | Low |
| Priority | Low |
| Status | New |

**Steps to Reproduce:**
1. Open the Amazon application.
2. Tap the Search bar.
3. Enter special characters (`@#$%^`).
4. Submit the search.

**Expected Result:** An appropriate no-results message should be displayed.

**Actual Result:** Irrelevant search results were displayed instead of a no-results message. The application remained stable.

## 🛠️ Skills Demonstrated

- Manual Testing
- Functional Testing
- Mobile Application Testing
- UI and Usability Testing
- Compatibility Testing
- Test Case Design
- Test Execution
- Positive and Negative Testing
- Defect Identification and Reporting
- Test Documentation
- Severity and Priority Analysis

## 📚 Testing Concepts Learned

- Test Scenario and Test Case
- Expected Result vs. Actual Result
- Severity vs. Priority
- Defect Life Cycle
- Smoke Testing
- Sanity Testing
- Regression Testing
- Test Execution and Reporting

## 📂 Project Structure

```text
Amazon-Mobile-App-Manual-Testing/
│
├── README.md
│
└── Test-Case-Document/
    └── Amazon_Mobile_App_Test_Cases.pdf
```

## 👩‍💻 Author

**Sai Sangeetha Padakanti**

B.Tech – Computer Science and Engineering

- GitHub: https://github.com/saisangeetha-25
- LinkedIn: https://www.linkedin.com/in/saisangeethapadakanti/

---

**Disclaimer:** This is an independent learning project created for educational and practical manual testing purposes. Amazon is a trademark of Amazon.com, Inc. This project is not affiliated with or endorsed by Amazon.
