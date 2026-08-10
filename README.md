

# ✈️ Airline Bug Reporting & Automation System







---

# 📌 Overview

The **Airline Bug Reporting & Automation System** is a Selenium-based automation testing project designed to simulate real-world QA workflows for airline reservation systems.

This project validates critical airline functionalities such as:

- ✈️ Flight Searchs
- 🔐 Login Authentication
- 🧾 Booking Validation
- 🐞 Bug Detection & Reporting
- 📸 Screenshot Capture on Failure
- 📊 Test Execution Logging

The framework follows the **Page Object Model (POM)** architecture for scalability and maintainability.

---

# 🧠 Key Highlights

✅ Selenium WebDriver Automation
✅ Java + TestNG Framework
✅ Maven Build Management
✅ Page Object Model (POM)
✅ Cross-Browser Ready
✅ Screenshot Capture on Failure
✅ Reusable Utility Functions
✅ Automated Test Reporting

---

# 🏗️ Project Architecture

```text
Airline-Automation-System
│
├── src
│   ├── main/java
│   │   ├── pages
│   │   ├── utilities
│   │   └── base
│   │
│   └── test/java
│       ├── tests
│       └── listeners
│
├── screenshots
├── reports
├── test-output
├── pom.xml
└── README.md
```

---

# ⚙️ Tech Stack

| Technology         | Usage                 |
| ------------------ | --------------------- |
| Java               | Programming Language  |
| Selenium WebDriver | Browser Automation    |
| TestNG             | Test Framework        |
| Maven              | Dependency Management |
| Git & GitHub       | Version Control       |
| ChromeDriver       | Browser Execution     |

---

# 🔄 Automation Workflow






---

# 🧪 Sample Test Scenario

## ✅ Test Case: Invalid Login Validation

### Steps:

1. Open airline booking website
2. Enter invalid username/password
3. Click Login button

### Expected Result:

System should display proper validation message.

### Actual Result:

Application throws authentication failure.

### Status:

❌ Failed

---

# 🐛 Bug Report Example

| Field       | Details                             |
| ----------- | ----------------------------------- |
| Bug ID      | AIR-001                             |
| Module      | Authentication                      |
| Severity    | High                                |
| Priority    | Critical                            |
| Environment | Chrome / Windows                    |
| Description | Login fails for invalid credentials |
| Expected    | Validation message                  |
| Actual      | System crash                        |
| Status      | Open                                |

---

# 📸 Screenshots

Store execution screenshots inside:

```bash
/screenshots
```

Example:

```bash
screenshots/login_failure.png
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/airline-bug-report.git
cd airline-bug-report
```

---

## 2️⃣ Install Dependencies

```bash
mvn clean install
```

---

## 3️⃣ Execute Tests

```bash
mvn test
```

---

# 📊 Reporting

The framework supports:

- ✅ TestNG Reports
- ✅ Console Logs
- ✅ Screenshot Reports
- 🔜 Allure Reports
- 🔜 Extent Reports

---

# 🌟 Future Enhancements

- 🚀 CI/CD Integration using GitHub Actions
- ☁️ BrowserStack Cloud Execution
- ⚡ Parallel Test Execution
- 📈 Allure Reporting Dashboard
- 🤖 AI-based Defect Prediction
- 🧪 API Automation Integration

---

# 🛡️ Design Pattern Used

## 📌 Page Object Model (POM)

Benefits:

- Reusable code
- Better maintainability
- Reduced duplication
- Scalable framework design

---

# 📷 Demo Preview

---

# 📈 GitHub Stats

---

# 🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Submit Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

## Shruti Sinha

---
