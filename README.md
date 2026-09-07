<div align="center">
<br>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=1800&pause=500&color=58A6FF&center=true&vCenter=true&repeat=true&width=850&height=35&lines=%5B+SYSTEM+ONLINE+%5D;%3E%3E+INITIALIZING+QA+AUTOMATION...;%3E%3E+FLIGHT+SYSTEM+UNDER+TEST;%3E%3E+BUG+DETECTION+ENGINE+ACTIVE;%3E%3E+TEST+EXECUTION+IN+PROGRESS..." alt="System Status">
<br><br>

# ✈️ AIRLINE
# **BUG REPORTING & AUTOMATION SYSTEM**

<br>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:161B22,100:0D1117&height=4&section=header" width="85%">
<br>

### `QA AUTOMATION`  •  `SELENIUM`  •  `TESTNG`  •  `POM`

<br>
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=900&color=8B949E&center=true&vCenter=true&repeat=true&width=900&height=30&lines=SEARCH+%E2%9C%88%EF%B8%8F+BOOK+%E2%9C%88%EF%B8%8F+VALIDATE+%E2%9C%88%EF%B8%8F+REPORT;AUTOMATE+%E2%86%92+EXECUTE+%E2%86%92+DETECT+%E2%86%92+REPORT;FROM+TEST+CASE+TO+ACTIONABLE+BUG+REPORT" alt="Automation Workflow">
<br><br>

<img src="https://img.shields.io/badge/🧪_TEST_AUTOMATION-READY-238636?style=for-the-badge&labelColor=0D1117">
<img src="https://img.shields.io/badge/🐞_BUG_DETECTION-ACTIVE-da3633?style=for-the-badge&labelColor=0D1117">
<img src="https://img.shields.io/badge/📸_FAILURE_CAPTURE-ENABLED-8957E5?style=for-the-badge&labelColor=0D1117">
<img src="https://img.shields.io/badge/📊_TEST_REPORTING-ONLINE-1F6FEB?style=for-the-badge&labelColor=0D1117">

<br><br>
<img src="https://skillicons.dev/icons?i=java,selenium,maven,git,github" alt="Technology Stack">
<br><br>

<table>
<tr>
<td align="center">
<b>✈️ FLIGHT SYSTEM</b>
<br>
<code>UNDER TEST</code>
</td>
<td align="center">
<b>🧪 TEST ENGINE</b>
<br>
<code>TESTNG + SELENIUM</code>
</td>
<td align="center">
<b>🐞 DEFECT ENGINE</b>
<br>
<code>BUG DETECTION</code>
</td>
<td align="center">
<b>📸 EVIDENCE</b>
<br>
<code>SCREENSHOTS + LOGS</code>
</td>
</tr>
</table>

</div>

<br>

## 📖 Overview

The **Airline Bug Reporting & Automation System** is a QA automation framework built to test an airline booking flow end-to-end — search, book, and validate a flight — while automatically capturing evidence (screenshots + logs) whenever a test fails, and compiling results into a structured bug/test report.

It follows the **Page Object Model (POM)** design pattern for maintainable, scalable test code, and is built entirely in **Java** with **Selenium WebDriver** and **TestNG**.

<br>

## ✨ Features

- 🔍 **Automated flight search** — validates search results for various route/date combinations
- 🧾 **Automated booking flow** — end-to-end simulation of selecting a flight and completing booking
- ✅ **Assertion-based validation** — checks booking confirmations, pricing, and error states against expected outcomes
- 🐞 **Automatic bug capture** — failed assertions are logged with contextual details for reporting
- 📸 **Screenshot-on-failure** — every failed test automatically saves a screenshot for debugging
- 📊 **Structured test reports** — TestNG-generated HTML reports summarizing pass/fail results across the suite
- 🧱 **Page Object Model architecture** — each page of the airline site is its own class, keeping locators and actions decoupled from test logic

<br>

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| Browser Automation | Selenium WebDriver |
| Test Framework | TestNG |
| Build Tool | Maven |
| Design Pattern | Page Object Model (POM) |
| Version Control | Git & GitHub |

<br>

## 📁 Project Structure

```
airline-bug-reporting-automation/
├── src/
│   ├── main/java/
│   │   └── pages/                 # Page Object classes (SearchPage, BookingPage, etc.)
│   └── test/java/
│       ├── tests/                 # TestNG test classes
│       └── utils/                 # Helpers: screenshot capture, waits, reporting
├── screenshots/                   # Auto-captured failure screenshots
├── test-output/                   # TestNG-generated reports
├── pom.xml                        # Maven dependencies & build config
└── README.md
```

<br>

## ⚙️ How to Run

**Prerequisites:** Java JDK 11+, Maven, Chrome browser

```bash
# Clone the repository
git clone https://github.com/Shrutishinha/airline-bug-reporting-automation.git
cd airline-bug-reporting-automation

# Install dependencies
mvn clean install

# Run the full test suite
mvn test

# Run a specific test class
mvn test -Dtest=FlightBookingTest
```

Test results are generated in `test-output/` (TestNG HTML report), and failure screenshots are saved automatically to `screenshots/`.

<br>

## 🔄 Workflow

```
SEARCH → BOOK → VALIDATE → REPORT
```

1. **Search** — automate entering origin, destination, and travel dates
2. **Book** — automate selecting a flight and completing passenger/booking details
3. **Validate** — assert the outcome matches expected behavior (confirmation shown, correct price, valid error handling)
4. **Report** — on failure, capture a screenshot + log details into the test report as a trackable bug

<br>

## 🧩 Design Pattern: Page Object Model

Each page of the airline site (Search, Results, Booking, Confirmation) is represented as its own Java class containing element locators and reusable action methods. Test classes call these methods rather than interacting with raw locators directly — so if the UI changes, only the Page class needs updating, not every test that uses it.

<br>

## 🚀 Possible Enhancements

- [ ] Integrate with CI/CD (GitHub Actions/Jenkins) for automated runs on every push
- [ ] Add cross-browser testing (Firefox, Edge) via Selenium Grid
- [ ] Add data-driven testing with TestNG `@DataProvider` for multiple route/date combinations
- [ ] Integrate Extent Reports for richer, more visual test reporting
- [ ] Add API-level validation alongside UI tests for faster feedback

<br>

## 👤 Author

**Shruti Sinha**
B.Tech CSE, Dronacharya College of Engineering
[LinkedIn](https://linkedin.com/in/shruti-sinha) • [GitHub](https://github.com/Shrutishinha)

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:161B22,50:1F6FEB,100:0D1117&height=100&section=header&reversal=true" width="100%">
</div>
