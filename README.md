# 📂 OpenCart-Manual QA Repository 

This repository contains **Manual QA testing artifacts** for the [OpenCart Demo Application](https://demo.opencart.com/).  
It demonstrates the **end-to-end QA process**, including test design, execution, bug reporting, and requirement traceability.

---

## 📑 Contents

- **Test Scenarios** → High-level test scenarios covering different OpenCart modules *(Excel file)*  
- **Test Execution Results** → Execution status (Pass/Fail) with remarks *(Excel file)*  
- **Bug Report** → Documented defects with severity & priority *(Excel file)*  
- **RTM (Requirement Traceability Matrix)** → Mapping requirements to test cases *(Excel file)*  

---

## 🔍 Sample Test Scenario (Preview)

| ID   | Module     | Scenario Description              | Expected Result |
|------|------------|-----------------------------------|----------------|
| TS01 | Login      | Verify login with valid data      | User logged in |
| TS02 | Login      | Verify login with invalid data    | Error message  |

👉 Full file: [OpenCart-Test Scenarios.xlsx]

---

## ✅ Sample Test Execution (Preview)

| ID   | Scenario                      | Status | Remarks              |
|------|-------------------------------|--------|---------------------|
| TS01 | Login with valid credentials  | Pass   | Working as expected |
| TS02 | Login with invalid data       | Fail   | Error message not displayed |

👉 Full file: [OpenCart-TestExecution Results.xlsx]

---

## 🐞 Bug Report (Preview)

| Bug ID | Module | Description                     | Severity | Status |
|--------|--------|---------------------------------|----------|--------|
| BUG01  | Login  | Invalid login does not show error | High     | Open   |
| BUG02  | Cart   | Items not removed properly        | Medium   | Fixed  |

👉 Full file: [OpenCart-BugReport.xlsx]

---

## 🔗 Requirement Traceability Matrix (RTM)

| Requirement ID | Linked Test Case | Status |
|----------------|------------------|--------|
| R001           | TS01, TS02       | Tested |
| R002           | TS03, TS04       | Pending |

👉 Full file: [OpenCart-RTM.xlsx]

---

## 🛠 Tools Used
- Microsoft Excel (for test design & execution)  
- OpenCart Demo Application (test site)  

---

## 📌 Notes
This repo is part of my QA portfolio and showcases my ability to create and manage **manual QA documentation**.  
Future updates will include **automation scripts with Python, Selenium & Playwright**.
