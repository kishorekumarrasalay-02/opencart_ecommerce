# 🛒 OpenCart E-Commerce - Manual Testing Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Testing](https://img.shields.io/badge/Testing-Manual-blue.svg)](https://github.com/kishorekumarrasalay-02/opencart_ecommerce)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)](https://github.com/kishorekumarrasalay-02/opencart_ecommerce)

A comprehensive end-to-end manual testing project for an OpenCart-based e-commerce web application, demonstrating complete Software Testing Life Cycle (STLC) implementation with a focus on quality assurance, defect tracking, and requirement traceability.

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Key Achievements](#-key-achievements)
- [Tools & Technologies](#-tools--technologies)
- [Testing Scope](#-testing-scope)
- [Project Structure](#-project-structure)
- [Testing Deliverables](#-testing-deliverables)
- [Key Contributions](#-key-contributions)
- [Getting Started](#-getting-started)
- [Test Execution Summary](#-test-execution-summary)
- [Author](#-author)

---

## 🎯 Project Overview

This project showcases professional manual testing capabilities applied to a **live OpenCart e-commerce platform**, ensuring quality and reliability across critical user workflows. The project covers complete STLC phases from requirement analysis to defect closure, with emphasis on functional testing, database validation, and regression testing.

### Application Under Test (AUT)
- **Platform:** OpenCart E-Commerce Web Application
- **Environment:** Live Production Environment
- **Testing Type:** Black Box Testing (Functional, UI/UX, Database)
- **Methodology:** SDLC/STLC (Agile Framework)

---

## 🏆 Key Achievements

✅ **25+ Test Cases Designed & Executed** covering positive, negative, and boundary scenarios  
✅ **100% Requirements Coverage** through comprehensive RTM (Requirement Traceability Matrix)  
✅ **8+ Functional Defects Identified** with detailed reproduction steps and severity classification  
✅ **Zero Critical Bugs in Production** post-regression testing  
✅ **Complete Defect Life Cycle Management** ensuring timely resolution of all issues  
✅ **SQL-Based Data Validation** for backend data integrity verification  
✅ **Version Controlled Test Artifacts** using Git/GitHub for centralized repository management  

---

## 🛠️ Tools & Technologies

| Category | Tools/Technologies |
|----------|-------------------|
| **Testing Type** | Manual Testing |
| **Test Design** | Test Case Design, Boundary Value Analysis, Equivalence Partitioning |
| **Defect Tracking** | Defect Life Cycle Management, Bug Reporting |
| **Database** | MySQL (Backend Validation & Data Integrity Testing) |
| **Documentation** | MS Excel (Test Cases, RTM, Bug Reports, Test Execution Reports) |
| **Methodologies** | SDLC/STLC (Software Development & Testing Life Cycle) |
| **Version Control** | Git & GitHub |
| **Testing Types** | Smoke Testing, Regression Testing, Functional Testing, Database Testing |

---

## 🎯 Testing Scope

### Core Modules Tested

#### 1. **User Registration** 
- Valid/Invalid email formats
- Password strength validation
- Mandatory field validation
- Duplicate account prevention
- Privacy policy acceptance

#### 2. **Login/Logout**
- Valid/Invalid credentials
- Session management
- "Remember Me" functionality
- Security validation
- Logout confirmation

#### 3. **Password Recovery (Forgot Password)**
- Email verification
- Reset link generation
- Password reset workflow
- Security token validation

#### 4. **Account Management**
- Profile information updates
- Password change functionality
- Newsletter subscription
- Account deletion

#### 5. **Product Search**
- Search functionality accuracy
- Empty search handling
- Special character validation
- Result count verification

---

## 📂 Project Structure

```
opencart_ecommerce/
│
├── 📁 FRS/                                    # Functional Requirement Specifications
│   ├── FRS_OpenCart_Ecommerce.xlsx
│   └── FRS_OpenCart_Ecommerce.pdf
│
├── 📁 Test_Cases/                            # Comprehensive Test Cases
│   ├── Register_Test_Cases.xlsx
│   ├── Login_Test_Cases.xlsx
│   ├── Logout_Test_Cases.xlsx
│   ├── Forgot_Password_Test_Cases.xlsx
│   └── Account_Test_Cases.xlsx
│
├── 📁 RTM/                                   # Requirement Traceability Matrix
│   └── RTM_OpenCart.xlsx
│
├── 📁 Defect_Reports/                        # Bug Reports & Defect Logs
│   └── Sample_Defect_Report.xlsx
│
├── 📁 Test_Execution_Reports/                # Test Execution Summary
│   └── Test_Execution_Report.xlsx
│
├── 📄 LICENSE                                # MIT License
└── 📄 README.md                              # Project Documentation
```

---

## 📊 Testing Deliverables

### 1. **Test Planning Documents**
- ✅ Functional Requirement Specifications (FRS)
- ✅ Test Plan outlining scope, objectives, and approach
- ✅ Test Strategy for each module

### 2. **Test Case Documentation**
- ✅ **25+ Detailed Test Cases** with:
  - Pre-conditions
  - Test steps
  - Expected results
  - Actual results
  - Pass/Fail status
  - Priority & Severity classification

### 3. **Requirement Traceability Matrix (RTM)**
- ✅ Complete mapping between requirements and test cases
- ✅ 100% bidirectional traceability
- ✅ Coverage analysis ensuring no gaps

### 4. **Defect Reports**
- ✅ **8+ Bug Reports** documented with:
  - Defect ID and summary
  - Steps to reproduce
  - Expected vs Actual behavior
  - Screenshots/Evidence
  - Severity and Priority
  - Environment details
  - Status tracking (New → Assigned → Fixed → Closed)

### 5. **Test Execution Reports**
- ✅ Smoke testing results
- ✅ Regression testing summary
- ✅ Test metrics and coverage statistics
- ✅ Defect distribution analysis

---

## 💡 Key Contributions

### 🔍 **Test Planning & Execution**
Designed and executed **25+ comprehensive test cases** covering:
- ✅ Positive scenarios (Happy path testing)
- ✅ Negative scenarios (Error handling)
- ✅ Boundary value scenarios (Edge cases)
- ✅ End-to-end user workflows

**Result:** Successfully identified **8+ functional defects** across core modules with zero escapes to production.

---

### 📐 **Requirements Coverage**
Created and maintained a **Requirement Traceability Matrix (RTM)** ensuring:
- ✅ 100% alignment between business requirements and test cases
- ✅ Bidirectional traceability for impact analysis
- ✅ Gap identification in requirement coverage

**Result:** Achieved **100% requirements coverage** with full traceability.

---

### 🐛 **Defect Management**
Implemented comprehensive defect tracking:
- ✅ Documented detailed bug reports with clear reproduction steps
- ✅ Attached screenshots and supporting evidence
- ✅ Classified defects by severity (Critical, Major, Minor, Trivial)
- ✅ Tracked defects through complete lifecycle (Open → Assigned → Fixed → Verified → Closed)

**Result:** Ensured **100% resolution** of all critical and major defects before production deployment.

---

### 💾 **Database Validation**
Performed SQL-based backend testing using **MySQL**:
- ✅ Verified user registration data persistence
- ✅ Validated search result accuracy through database queries
- ✅ Ensured data integrity across CRUD operations
- ✅ Cross-verified UI data with database records

**Result:** Identified **data inconsistencies** between frontend and backend, ensuring data accuracy.

---

### 🔄 **Regression Testing**
Executed comprehensive regression testing cycles:
- ✅ **Smoke Testing** post-deployment to validate critical workflows
- ✅ **Regression Testing** to ensure bug fixes didn't introduce new defects
- ✅ Re-testing of fixed defects for verification
- ✅ Impact analysis for code changes

**Result:** Reduced potential production issues by **ensuring zero impact** on existing functionality.

---

### 📚 **Version Control & Collaboration**
Utilized **Git/GitHub** for test artifact management:
- ✅ Centralized repository for all test plans, cases, and scripts
- ✅ Version control for test documentation
- ✅ Collaborative review process for test artifacts
- ✅ Change tracking and history maintenance

**Result:** Maintained **organized, accessible, and traceable** testing documentation.

---

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel (for viewing test artifacts)
- PDF Reader (for FRS documents)
- MySQL Workbench (optional, for database validation review)
- Git (for cloning the repository)

### Installation & Review Steps

#### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/kishorekumarrasalay-02/opencart_ecommerce.git
cd opencart_ecommerce
```

#### 2️⃣ **Review Functional Requirements**
Navigate to the `FRS/` folder to understand the application requirements:
```bash
cd FRS/
# Open FRS_OpenCart_Ecommerce.xlsx or .pdf
```

#### 3️⃣ **Explore Test Cases**
Navigate to `Test_Cases/` folder to review detailed test scenarios:
```bash
cd Test_Cases/
# Open individual test case files for each module
```

**Each test case includes:**
- Test Case ID
- Test Scenario
- Pre-conditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status (Pass/Fail)
- Priority & Severity

#### 4️⃣ **Check Requirement Traceability**
Navigate to `RTM/` folder to verify requirements coverage:
```bash
cd RTM/
# Open RTM_OpenCart.xlsx
```

**RTM provides:**
- Requirement ID mapping to Test Case ID
- Coverage percentage
- Testing status for each requirement

#### 5️⃣ **Review Defect Reports**
Navigate to `Defect_Reports/` folder to examine identified bugs:
```bash
cd Defect_Reports/
# Open Sample_Defect_Report.xlsx
```

**Defect reports include:**
- Defect ID & Summary
- Steps to Reproduce
- Expected vs Actual Behavior
- Screenshots
- Severity & Priority
- Status & Resolution

#### 6️⃣ **Analyze Test Execution Summary**
Navigate to `Test_Execution_Reports/` for overall testing metrics:
```bash
cd Test_Execution_Reports/
# Open Test_Execution_Report.xlsx
```

---

## 📈 Test Execution Summary

| Metric | Count | Percentage |
|--------|-------|------------|
| **Total Test Cases** | 25+ | 100% |
| **Test Cases Executed** | 25+ | 100% |
| **Test Cases Passed** | 17+ | ~68% |
| **Test Cases Failed** | 8+ | ~32% |
| **Defects Identified** | 8+ | - |
| **Defects Fixed** | 8+ | 100% |
| **Requirements Covered** | All | 100% |
| **Regression Cycles** | 2+ | - |

### Test Coverage Breakdown

```
User Registration:     ████████████████░░░░  80%
Login/Logout:          ███████████████████░  95%
Password Recovery:     █████████████████░░░  85%
Account Management:    ████████████████░░░░  80%
Product Search:        ██████████████████░░  90%
```

### Defect Distribution by Severity

| Severity | Count | Percentage |
|----------|-------|------------|
| 🔴 Critical | 1 | 12.5% |
| 🟠 Major | 3 | 37.5% |
| 🟡 Minor | 3 | 37.5% |
| 🟢 Trivial | 1 | 12.5% |

---

## 📸 Sample Test Artifacts

### Test Case Example
```
Test Case ID: TC_REG_001
Module: User Registration
Priority: High | Severity: Critical

Test Scenario: Verify user registration with valid credentials

Pre-conditions: 
- Application is accessible
- Database is connected

Test Steps:
1. Navigate to Registration page
2. Enter valid First Name
3. Enter valid Last Name
4. Enter valid Email address
5. Enter valid Password (8+ chars, mixed case)
6. Confirm Password
7. Accept Privacy Policy
8. Click "Continue"

Expected Result: 
- User should be successfully registered
- Confirmation message displayed
- Redirect to "My Account" page
- User data saved in database

Actual Result: As Expected

Status: ✅ PASS
```

### Defect Report Example
```
Defect ID: BUG_001
Summary: Password field accepts less than 4 characters

Module: User Registration
Severity: Major | Priority: High

Steps to Reproduce:
1. Go to Registration page
2. Enter password with 3 characters "abc"
3. Submit the form

Expected Result: 
Error message: "Password must be at least 4 characters"

Actual Result: 
User is registered successfully with 3-character password

Environment: Chrome 120.0, Windows 11
Status: Fixed & Verified
```

---

## 🎓 Skills Demonstrated

- ✅ **Manual Testing Expertise** - Comprehensive test case design and execution
- ✅ **SDLC/STLC Knowledge** - Understanding of complete software testing lifecycle
- ✅ **Defect Life Cycle Management** - From identification to closure
- ✅ **SQL & Database Testing** - Backend validation and data integrity checks
- ✅ **Test Documentation** - Professional test artifacts creation
- ✅ **Requirement Analysis** - RTM creation and traceability management
- ✅ **Version Control** - Git/GitHub for test repository management
- ✅ **Attention to Detail** - Identification of edge cases and boundary scenarios
- ✅ **Analytical Thinking** - Root cause analysis and defect investigation

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Kishore Kumar R**

📞 **Mobile:** +91-9490946159  
📧 **Email:** kishorekumarrasalay05@gmail.com  
💼 **LinkedIn:** [linkedin.com/in/kishorekumarrasalay](https://linkedin.com/in/kishorekumarrasalay)  
🐙 **GitHub:** [github.com/kishorekumarrasalay-02](https://github.com/kishorekumarrasalay-02)

---

## ⭐ Acknowledgments

Special thanks to:
- OpenCart community for the e-commerce platform
- Testing community for best practices and methodologies
- Peers and mentors for valuable feedback

---

<div align="center">

### ⭐ If you found this project helpful, please consider giving it a star! ⭐

</div>
