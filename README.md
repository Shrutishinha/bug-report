# ✈️ Airline Bug Reporting & Automation System

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=220&section=header&text=Airline%20Bug%20Reporting%20%26%20Automation&fontSize=28&fontColor=58A6FF&animation=fadeIn&fontAlignY=38"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Selenium+Test+Automation;Java+%7C+TestNG+%7C+Maven;Page+Object+Model+%7C+POM;Automated+Validation+%26+Bug+Reporting"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
  <img src="https://img.shields.io/badge/TestNG-Testing-F85149?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
  <img src="https://img.shields.io/badge/POM-Design%20Pattern-A371F7?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Automation-Testing-58A6FF?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Active-3FB950?style=flat-square"/>
  <img src="https://img.shields.io/badge/Framework-TestNG-58A6FF?style=flat-square"/>
</p>

---

## 📌 Overview

**Airline Bug Reporting & Automation System** is a Java-based Selenium automation project designed to automate important airline website workflows and validate application behavior through automated test cases.

The project combines **Selenium WebDriver, TestNG, Maven and Page Object Model (POM)** to create a structured and maintainable automation framework.

It focuses on:

* 🔎 Automated flight search
* 🎫 Booking workflow automation
* ✅ Assertion-based validation
* 🐞 Automated bug identification
* 📸 Screenshot capture for failures
* 📊 TestNG test reports
* 🧩 Maintainable Page Object Model architecture

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Automate repetitive airline website testing tasks.
2. Validate important user workflows.
3. Detect unexpected application behavior.
4. Capture evidence when a test fails.
5. Generate structured test execution reports.
6. Maintain reusable and scalable automation code.

---

## 🚀 Key Features

| Feature          | Description                                |
| ---------------- | ------------------------------------------ |
| 🔎 Flight Search | Automates flight search functionality      |
| 🎫 Booking Flow  | Automates important booking steps          |
| ✅ Assertions     | Validates expected application behavior    |
| 🐞 Bug Detection | Identifies failures during execution       |
| 📸 Screenshots   | Captures screenshots for failed scenarios  |
| 📊 Test Reports  | Uses TestNG reporting                      |
| 🧩 POM           | Separates page elements and test logic     |
| 📦 Maven         | Manages dependencies and project execution |

---

## 🏗️ Project Architecture

```text
                ┌───────────────────────┐
                │     TestNG Tests      │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │    Page Object Model  │
                │         (POM)         │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │   Selenium WebDriver  │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │    Airline Website    │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │ Assertions & Results  │
                └───────────┬───────────┘
                            │
                    ┌───────┴────────┐
                    ▼                ▼
             ┌────────────┐   ┌─────────────┐
             │ Screenshot │   │ Test Report │
             └────────────┘   └─────────────┘
```

---

## 🔄 Automation Workflow

```text
SEARCH
   ↓
BOOK
   ↓
VALIDATE
   ↓
ASSERT
   ↓
CAPTURE FAILURE
   ↓
GENERATE REPORT
```

### Workflow Explanation

**1. Search**

The automation script performs the required flight search operations.

**2. Book**

The script navigates through the booking workflow.

**3. Validate**

Expected results are checked using assertions.

**4. Assert**

TestNG assertions determine whether the actual result matches the expected result.

**5. Capture Failure**

When a test fails, screenshot evidence can be captured for debugging.

**6. Generate Report**

TestNG generates execution results for reviewing passed and failed test cases.

---

## 🧪 Test Scenarios

The framework can be used to validate scenarios such as:

* Flight search with valid inputs
* Flight search with invalid inputs
* Source and destination selection
* Date selection
* Search result validation
* Flight selection
* Booking workflow validation
* Required-field validation
* Unexpected UI behavior
* Failed test screenshot capture

---

## 🛠️ Tech Stack

### Programming Language

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)

### Automation

![Selenium](https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=flat-square\&logo=selenium\&logoColor=white)

### Testing

![TestNG](https://img.shields.io/badge/TestNG-Testing-F85149?style=flat-square)

### Build Tool

![Maven](https://img.shields.io/badge/Maven-Build-C71A36?style=flat-square\&logo=apachemaven\&logoColor=white)

### Design Pattern

![POM](https://img.shields.io/badge/Page%20Object%20Model-POM-A371F7?style=flat-square)

### Version Control

![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square\&logo=git\&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square\&logo=github\&logoColor=white)

---

## 📂 Project Structure

```text
airline-bug-reporting-automation/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── pages/
│   │           ├── HomePage.java
│   │           ├── SearchPage.java
│   │           └── BookingPage.java
│   │
│   └── test/
│       └── java/
│           ├── tests/
│           │   └── AirlineTest.java
│           │
│           └── utils/
│               └── ScreenshotUtil.java
│
├── screenshots/
│
├── test-output/
│
├── pom.xml
│
└── README.md
```

> Update the individual Java filenames above if your actual project uses different class names.

---

## 🧩 Page Object Model

The project follows the **Page Object Model (POM)** design pattern.

Instead of placing all Selenium locators and actions directly inside test classes, page-specific elements and methods are organized into separate classes.

### Example

```java
public class SearchPage {

    private WebDriver driver;

    @FindBy(id = "from")
    WebElement fromCity;

    @FindBy(id = "to")
    WebElement toCity;

    public SearchPage(WebDriver driver) {
        this.driver = driver;
        PageFactory.initElements(driver, this);
    }

    public void enterFromCity(String city) {
        fromCity.sendKeys(city);
    }

    public void enterToCity(String city) {
        toCity.sendKeys(city);
    }
}
```

### Benefits of POM

* ♻️ Code reusability
* 🧹 Cleaner test classes
* 🔧 Easier maintenance
* 📈 Better scalability
* 🔍 Improved readability

---

## 🧪 Example TestNG Test

```java
@Test
public void searchFlightTest() {

    SearchPage searchPage = new SearchPage(driver);

    searchPage.enterFromCity("Delhi");
    searchPage.enterToCity("Mumbai");

    // Perform search
    // Validate expected result
}
```

---

## 🐞 Bug Reporting Flow

When an unexpected behavior occurs:

```text
Test Execution
      ↓
Assertion Failure
      ↓
TestNG Detects Failure
      ↓
Capture Screenshot
      ↓
Store Evidence
      ↓
Review Failure
      ↓
Bug Investigation
```

This helps in connecting the automated test failure with visual evidence for easier debugging.

---

## 📸 Screenshot Evidence

Screenshots can be stored inside:

```text
/screenshots/
```

Example:

```text
screenshots/
├── search_failure.png
├── booking_failure.png
└── validation_failure.png
```

Screenshots provide visual evidence of the application state at the time of failure.

---

## 📊 Test Execution

The project uses **TestNG** for test execution and reporting.

Run the tests using Maven:

```bash
mvn clean test
```

For compiling the project:

```bash
mvn clean compile
```

To skip tests during packaging:

```bash
mvn clean package -DskipTests
```

---

## 📋 Maven Configuration

The project uses Maven for dependency management.

Example dependencies:

```xml
<dependencies>

    <!-- Selenium -->
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.XX.X</version>
    </dependency>

    <!-- TestNG -->
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.XX.X</version>
        <scope>test</scope>
    </dependency>

</dependencies>
```

> Replace `4.XX.X` and `7.XX.X` with the versions used in your actual `pom.xml`.

---

## ⚙️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shrutishinha/airline-bug-reporting-automation.git
```

### 2️⃣ Navigate to the Project

```bash
cd airline-bug-reporting-automation
```

### 3️⃣ Open the Project

Open the project in:

* IntelliJ IDEA
* Eclipse
* VS Code

### 4️⃣ Install Maven Dependencies

```bash
mvn clean install
```

### 5️⃣ Execute Tests

```bash
mvn test
```

---

## 🔍 Testing Approach

The automation framework follows a structured testing approach:

| Testing Area          | Approach           |
| --------------------- | ------------------ |
| Functional Testing    | Selenium WebDriver |
| UI Testing            | Selenium           |
| Regression Testing    | TestNG             |
| Validation            | TestNG Assertions  |
| Failure Evidence      | Screenshots        |
| Test Organization     | POM                |
| Dependency Management | Maven              |

---

## 📈 Advantages

### ⚡ Faster Execution

Automates repetitive manual testing tasks.

### 🔁 Reusable Tests

Test cases can be executed repeatedly with minimal manual effort.

### 🐞 Better Debugging

Screenshots help identify the application state when failures occur.

### 🧩 Maintainable Architecture

POM separates page-level implementation from test logic.

### 📊 Structured Reporting

TestNG provides organized test execution results.

---

## 🔮 Future Enhancements

Planned improvements include:

* [ ] GitHub Actions CI/CD integration
* [ ] Jenkins pipeline
* [ ] Cross-browser testing
* [ ] Selenium Grid
* [ ] TestNG DataProvider
* [ ] Extent Reports
* [ ] API validation
* [ ] Parallel test execution
* [ ] Advanced logging
* [ ] Automated bug-report generation

---

## 🎓 Learning Outcomes

Through this project, I strengthened my understanding of:

* Java-based test automation
* Selenium WebDriver
* TestNG
* Maven
* Page Object Model
* Automated assertions
* UI validation
* Failure handling
* Screenshot-based debugging
* Test reporting
* Git/GitHub workflow

---

## 💼 Why This Project Matters

This project demonstrates practical experience in **Software Testing and Test Automation** rather than only theoretical knowledge.

It showcases the ability to:

```text
Design Test Cases
       ↓
Automate Workflows
       ↓
Validate Results
       ↓
Detect Failures
       ↓
Capture Evidence
       ↓
Generate Reports
```

---

## 📌 Project Highlights

<p align="center">

| Category        | Details                     |
| --------------- | --------------------------- |
| Language        | Java                        |
| Automation      | Selenium WebDriver          |
| Testing         | TestNG                      |
| Build Tool      | Maven                       |
| Architecture    | Page Object Model           |
| Version Control | Git & GitHub                |
| Domain          | Airline / Travel Automation |

</p>

---

## 👩‍💻 Author

### Shruti Sinha

**B.Tech CSE | Software Development | Data Analytics | AI/ML | Test Automation**

<p align="center">
  <a href="https://github.com/Shrutishinha">
    <img src="https://img.shields.io/badge/GitHub-Shrutishinha-181717?style=for-the-badge&logo=github"/>
  </a>

  <a href="https://linkedin.com/in/shruti-sinha">
    <img src="https://img.shields.io/badge/LinkedIn-Shruti%20Sinha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=120&section=footer"/>
</p>

<p align="center">
  <b>Built with Java • Selenium • TestNG • Maven</b>
</p>
