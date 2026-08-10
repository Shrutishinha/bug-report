<div align="center">

# ✈️ Airline Bug Reporting & Automation System

### 🚀 Selenium-Based Test Automation Framework for Airline Reservation Systems

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk)
![Selenium](https://img.shields.io/badge/Selenium-Automation-green?style=for-the-badge&logo=selenium)
![TestNG](https://img.shields.io/badge/TestNG-Testing-red?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-Build-blue?style=for-the-badge&logo=apachemaven)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black?style=for-the-badge&logo=github)

*A scalable Selenium automation framework that validates core airline booking functionalities while following industry-standard QA practices.*

</div>

---

# 📖 Overview

The **Airline Bug Reporting & Automation System** is a Selenium WebDriver automation framework developed to simulate **real-world Quality Assurance (QA) workflows** for airline reservation applications.

The project automates critical user journeys including authentication, flight search, booking validation, and bug reporting while generating execution logs and screenshots for failed test cases.

Designed using the **Page Object Model (POM)** architecture, the framework promotes modularity, maintainability, and reusability.

---

# ✨ Features

- ✈️ Flight Search Automation
- 🔐 Login Authentication Testing
- 🎫 Booking Validation
- ❌ Negative Test Scenarios
- 📸 Automatic Screenshot Capture on Failure
- 📊 Test Execution Reports
- 📝 Bug Reporting Structure
- ♻️ Reusable Utility Classes
- 📁 Page Object Model (POM)
- 🌐 Cross-Browser Ready
- ⚡ Maven Build Support

---

# 🎯 Objectives

- Automate repetitive airline testing workflows.
- Improve software quality through regression testing.
- Detect UI and functional defects early.
- Generate reproducible bug reports.
- Reduce manual testing effort.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| ☕ Java | Programming Language |
| 🌐 Selenium WebDriver | Browser Automation |
| 🧪 TestNG | Test Execution Framework |
| 📦 Maven | Dependency Management |
| 🖥️ ChromeDriver | Browser Driver |
| 📂 Git & GitHub | Version Control |
| 📝 Log Reports | Execution Logging |

---

# 🏗️ Project Structure

```text
Airline-Bug-Reporting-System
│
├── src
│   ├── main
│   │   └── java
│   │       ├── base
│   │       ├── pages
│   │       └── utilities
│   │
│   └── test
│       └── java
│           ├── tests
│           └── listeners
│
├── screenshots
├── reports
├── test-output
├── pom.xml
├── testng.xml
└── README.md
```

---

# ⚙️ Framework Architecture

```text
                 TestNG
                    │
                    ▼
             Test Classes
                    │
                    ▼
          Page Object Model
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
   Utility Classes         Base Class
        │                       │
        └───────────┬───────────┘
                    ▼
             Selenium WebDriver
                    │
                    ▼
             Airline Web Portal
```

---

# 🔄 Automation Workflow

```text
Start Test
      │
      ▼
Launch Browser
      │
      ▼
Open Airline Website
      │
      ▼
Execute Test Case
      │
      ▼
Validate Expected Result
      │
 ┌────┴─────┐
 │          │
Pass      Fail
 │          │
 │      Capture Screenshot
 │          │
 └──────┬───┘
        ▼
 Generate Report
        │
        ▼
   Close Browser
```

---

# 🧪 Sample Test Scenario

## ✅ Test Case: Invalid Login

### Test Steps

1. Launch browser
2. Navigate to airline website
3. Enter invalid credentials
4. Click **Login**
5. Validate error message

### Expected Result

The application should display a meaningful authentication error without crashing.

### Actual Result

Authentication failed successfully and the validation message was displayed.

### Status

✅ Passed

---

# 🐞 Sample Bug Report

| Field | Value |
|-------|-------|
| Bug ID | AIR-001 |
| Module | Login |
| Severity | High |
| Priority | Critical |
| Browser | Chrome |
| OS | Windows 11 |
| Environment | QA |
| Expected Result | Proper validation message |
| Actual Result | Application crashes |
| Status | Open |

---

# 📸 Screenshot Management

Failed test screenshots are automatically stored in:

```text
/screenshots
```

Example:

```text
screenshots/LoginFailure_001.png
```

---

# 📊 Reports

The framework supports:

- ✅ TestNG Reports
- ✅ Console Logs
- ✅ Failure Screenshots
- 🔜 Extent Reports
- 🔜 Allure Reports
- 🔜 HTML Dashboard

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Airline-Bug-Reporting-System.git
```

Move into the project

```bash
cd Airline-Bug-Reporting-System
```

Install dependencies

```bash
mvn clean install
```

Run all test cases

```bash
mvn test
```

---

# 📌 Supported Test Modules

- ✅ Login Testing
- ✅ Flight Search
- ✅ Booking Validation
- ✅ Passenger Details
- ✅ Payment Validation
- ✅ Error Message Verification
- ✅ Regression Testing

---

# 💡 Design Pattern

## 📂 Page Object Model (POM)

### Benefits

- Cleaner codebase
- Better maintainability
- High reusability
- Easy scalability
- Reduced code duplication
- Improved readability

---

# 📈 Future Enhancements

- 🚀 GitHub Actions CI/CD
- ☁️ BrowserStack Integration
- 🌍 Cross-Browser Parallel Execution
- 📊 Allure Dashboard
- 📑 Extent Reports
- 🧪 API Automation using Rest Assured
- 🤖 AI-Based Defect Prediction
- 📱 Mobile Automation with Appium
- 🐳 Docker Support

---

# 📷 Demo

> Add screenshots or GIFs of test execution here.

Example:

```
assets/demo.gif
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

## 👩‍💻 Author

### **Shruti Sinha**

**B.Tech CSE | QA Automation | Data Analytics | Java | Selenium | SQL**

⭐ If you found this project useful, don't forget to **Star** the repository!

</div>
