# 🛒 Daraz App Manual Testing Project
![Testing](https://img.shields.io/badge/Testing-Manual-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Test Cases](https://img.shields.io/badge/Test_Cases-79-orange)
![Passed](https://img.shields.io/badge/Passed-62-success)
![Failed](https://img.shields.io/badge/Failed-16-red)

---

## 📌 Project Overview

This project demonstrates **manual testing** performed on the Daraz mobile and desktop web application, focusing mainly on the **Sign Up, Login, and Password modules**.

The goal of this project is to showcase my understanding of:

- Software Testing Concepts  
- Test Design Techniques  
- Bug Reporting  
- Test Documentation  
- Test Execution & Analysis  

---

## 🎯 Modules Covered

- Sign Up (Desktop & Mobile)  
- Login (Email/Phone & Social Login)  
- Password Validation  

---

## 🧪 Testing Types Performed

- Functional Testing  
- UI Testing  
- Validation Testing  
- Negative Testing  
- Cross-platform Testing  

---

## 📊 Test Metrics

| SL | Metrics | Description | Result |
|----|--------|------------|--------|
| 1 | Total Test Cases | Total designed & executed | 79 |
| 2 | Passed | Successfully working features | 62 (78%) |
| 3 | Failed | Defects identified | 16 (20%) |
| 4 | Improvement | UI/UX suggestions | 1 (1%) |
| 5 | Blocked/No Run | Not executed | 0 |

---

## 📈 Test Execution Insight 🚀

Out of **79 test cases**, **100% were executed**.

- 78% passed successfully  
- 20% revealed defects  
- 1% suggested improvements  

---

## 🐞 Bug Severity Summary

| Severity | Count | Description |
|----------|------|------------|
| High | 6 | Core functionality issues (Login validation, Social login failure) |
| Medium | 7 | Validation & UI behavior issues |
| Low | 3 | UI text, spelling, minor UX issues |

---

## 📌 Module-wise Defect Distribution

| Module | Total Issues | Key Problems |
|--------|------------|-------------|
| Sign Up | 7 | Validation issues, Google signup failure, UI text bugs |
| Login (Password) | 6 | Missing validation, incorrect error handling |
| Login (Phone OTP) | 3 | OTP delay/failure, Google login issue |

---
## 📂 Project Structure


daraz-manual-testing/
│
├── Test Plan/
├── Mind Map/
├── Test Scenarios/
├── Test Cases/
├── Bug Reports/
├── Test Matrix/
└── Test Summary/


---
## 📂 Project Artifacts

### ✔️ Test Plan
Defines scope, objectives, testing strategy, and environment.

### ✔️ Test Scenarios
High-level user interaction scenarios.

### ✔️ Test Cases
Detailed test cases including:

- Test Data (valid/invalid inputs)  
- Expected Results  
- Actual Results  

### ✔️ Bug Reports
Includes:

- Severity & Priority  
- Defect Description  
- Evidence (Screenshots)  

### ✔️ Test Summary Report
Final execution report with insights and defect summary.

### ✔️ Test Matrix
Requirement-to-test case mapping.

### ✔️ Mind Map
Visual representation of test coverage.

---
## 📸 Bug Screenshots

### 🔹 Google Login Failure
![Google Login](./Bug%20Reports/google-login-failure.png)

### 🔹 Missing Validation (Login)
![Validation Bug](./Bug%20Reports/empty-login-no-validation.png)

### 🔹 Invalid Email Accepted
![Email Bug](./Bug%20Reports/invalid-email-validation.png)

### 🔹 OTP Issue
![OTP Bug](./Bug%20Reports/otp-second-attempt.png)

### 🔹 UI Text Error
![UI Bug](./Bug%20Reports/spelling-error-terms.png)

### 🔹 UI Behavior Issue
![UI Bug](./Bug%20Reports/underline-disappear.png)

---
## 🔍 Key Findings

### 🔴 Critical Issues
- Google authentication fails repeatedly  
- Login allows submission without required fields  

### 🟠 Major Issues
- Invalid email/phone formats not properly validated  
- OTP verification inconsistency  

### 🟡 Minor Issues
- Incorrect spelling ("Terms & condition")  
- Placeholder text not user-friendly  
- UI underline visibility issue  

---

## 💡 Recommendations

- Implement strict frontend validation before API call  
- Improve error messaging for better UX  
- Fix third-party authentication integration (Google login)  
- Maintain UI consistency across mobile and desktop  

---

## 🛠 Tools Used

- Microsoft Excel  
- Google Sheets  
- Xmind (Mind Map)  
- Web & Mobile Browsers  

---

## 👩‍💻 Author

**Nurjahan Smrity**  
BSc in Computer Science & Engineering  
Aspiring Full Stack QA Engineer  

---

## 📄 Project Description

**Daraz Manual Testing Project**  
Conducted end-to-end manual testing on authentication modules (Sign Up & Login) of the Daraz platform. Designed and executed 79 test cases, identified 16 defects related to validation, UI/UX, and third-party authentication. Prepared detailed test documentation including test cases, bug reports, and summary reports.

---

## 📎 Note

This project is created for **learning and portfolio purposes**, demonstrating practical **manual testing skills, defect analysis, and structured reporting**.
