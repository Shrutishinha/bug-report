# ✈️ Airline Bug Reporting & Automation System
hihi
<p align="center">
  <img src="https://media.giphy.com/media/xTiTnxpQ3ghPiB2Hp6/giphy.gif" width="500"/>
</p>

<p align="center">

  ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
  ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
  ![TestNG](https://img.shields.io/badge/TestNG-FF6F00?style=for-the-badge)
  ![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
  ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)

</p>

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

| Technology | Usage |
|------------|------|
| Java | Programming Language |
| Selenium WebDriver | Browser Automation |
| TestNG | Test Framework |
| Maven | Dependency Management |
| Git & GitHub | Version Control |
| ChromeDriver | Browser Execution |

---

# 🔄 Automation Workflow

<p align="center">

![Open](https://img.shields.io/badge/Open%20Website-0078D7?style=for-the-badge)
![Search](https://img.shields.io/badge/Search%20Flight-6A0DAD?style=for-the-badge)
![Validate](https://img.shields.io/badge/Validate%20Booking-228B22?style=for-the-badge)
![Capture](https://img.shields.io/badge/Capture%20Bug-DC143C?style=for-the-badge)

</p>

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

| Field | Details |
|------|---------|
| Bug ID | AIR-001 |
| Module | Authentication |
| Severity | High |
| Priority | Critical |
| Environment | Chrome / Windows |
| Description | Login fails for invalid credentials |
| Expected | Validation message |
| Actual | System crash |
| Status | Open |

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

<p align="center">
  <img src="screenshots/demo.gif" width="700"/>
</p>

---

# 📈 GitHub Stats

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&theme=tokyonight&hide_border=true"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=your-username&theme=tokyonight&hide_border=true"/>

</p>

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

<p align="center">

<a href="https://github.com/your-username">
  <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github"/>
</a>

<a href="https://linkedin.com/in/your-linkedin">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"/>
</a>

</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A2980,50:26D0CE,100:00C9FF&height=140&section=footer"/>
</p>
