# SoftwareTestingProject
This repository contains manual testing documentation. It includes a structured Test Plan, detailed Test Cases, and other QA artifacts designed to ensure application quality through end-to-end manual testing
# 🧪 Manual Testing Project

## 📌 Project Overview

Provide a high-level summary of the project under test.

- **Application Type: Web
- **Testing Type:** Manual Testing
- **Tested Modules:**  
  - Login & Authentication  
  - Dashboard  
  - Feature Modules (e.g., Orders, Reports, Campaigns)  
  - User Management  
  - Notifications or Integrations (if any)

---
## 📥 How to Use This Repository

This repository is structured to provide a clear view of the manual testing documentation for the project.

Follow these steps to explore or contribute:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/manual-testing-project.git
   cd manual-testing-project
---

## 🧭 Test Plan

The **Test Plan** defines the strategy, objectives, resources, and schedule for testing activities. It outlines the scope of testing, responsibilities, and risk mitigation.

📄 **File Location:** `./TestPlan/TestPlan.xlsx`

### Contents of the Test Plan:
- Test Objectives & Scope  
- In-scope / Out-of-scope Features  
- Test Types (Functional, UI, Compatibility, Regression)  
- Entry and Exit Criteria  
- Roles & Responsibilities  
- Test Environment  
- Risks and Contingencies  
- Deliverables and Milestones  

---

## ✅ Test Cases

This section contains **manual test cases** written to validate all key functionalities and edge scenarios of the application.

📄 **File Location:** `./TestCases/TestCases.xlsx`

### Each test case includes:
- Test Case ID  
- Test Title / Description  
- Module  
- Preconditions  
- Test Steps  
- Expected Result  
- Actual Result  
- Priority (High/Medium/Low)  
- Status (Pass/Fail/Blocked)  

#### 🧾 Sample Test Case Table:

| Test Case ID | Module       | Description                  | Priority | Status |
|--------------|--------------|------------------------------|----------|--------|
| TC_LOGIN_001 | Authentication | Login with valid credentials | High     | Passed |
| TC_DASH_002  | Dashboard     | Widgets visibility on load   | Medium   | Passed |
| TC_USER_004  | User Profile  | Save without mandatory field | High     | Failed |

---

## 🐞 Bug Reports

Bugs found during testing are documented with complete details and shared with the development team.

📄 **File Location:** `./BugReports/Bug_Report.xlsx`

### Each bug includes:
- Bug ID  
- Title  
- Module  
- Steps to Reproduce  
- Actual vs Expected Results  
- Severity / Priority  
- Status (Open / Fixed / Retest / Closed)  
- Screenshot / Log (if any)

---

## 🔁 Regression Testing

Regression testing is performed after every major release or hotfix to ensure no existing functionality is broken.

### Strategy:
- Identify critical and frequently used features
- Re-execute all high-priority test cases
- Track regression cycles in a separate sheet or tab

---

## 🌐 Compatibility Testing

Cross-browser and responsive design testing is performed to ensure the application works as expected in different environments.

### Tested Browsers:
- Google Chrome (Latest 2 versions)
- Mozilla Firefox
- Microsoft Edge
- Safari (macOS)

### Devices (Optional):
- Desktop
- Mobile (using DevTools or BrowserStack)

---

## 🧪 Test Execution Summary

Summarize test execution results from each cycle.

| Test Cycle | Total Cases | Passed | Failed | Blocked | Retested |
|------------|-------------|--------|--------|---------|----------|
| Cycle 1    | 50          | 45     | 4      | 1       | 0        |
| Cycle 2    | 50          | 48     | 1      | 1       | 5        |

---

## 👤 Author

- **Name:** Sneha Sandip Bobade
- **Role:** QA Analyst (Manual Testing)  
- **Experience:** 7+ Years  
- **Email:** snhabobade@gmail.com  
- **LinkedIn:**
---
