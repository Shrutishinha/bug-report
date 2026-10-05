<!-- ===================== HEADER ===================== -->

<div align="center">

# ✈️ Airline Bug Reporting & Automation System

### Java • Selenium WebDriver • TestNG • Maven • Page Object Model

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Selenium+Test+Automation;Java+%7C+TestNG+%7C+Maven;Page+Object+Model+%7C+POM;Automated+Validation+%26+Bug+Reporting" />
</p>

<p>
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
  <img src="https://img.shields.io/badge/TestNG-Testing-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
  <img src="https://img.shields.io/badge/POM-Design%20Pattern-58A6FF?style=for-the-badge"/>
</p>

</div>

---

## 📌 Project Overview

The **Airline Bug Reporting & Automation System** is a Selenium-based test automation project designed to automate and validate critical airline website workflows.

The system performs automated browser testing for scenarios such as:

- 🔎 Flight search
- 🛫 Flight selection
- 🎫 Booking workflow
- ✅ Functional validation
- ❌ Failure detection
- 📸 Automatic screenshot capture
- 🐞 Bug documentation
- 📊 Test execution reporting

The project follows the **Page Object Model (POM)** design pattern to maintain clean, reusable, and scalable automation code.

---

## 🎯 Objectives

The primary objectives of this project are:

- Automate repetitive airline website testing.
- Reduce manual testing effort.
- Validate important user workflows.
- Detect functional failures automatically.
- Capture screenshots when tests fail.
- Generate structured test reports.
- Maintain reusable Selenium page classes.
- Improve test maintainability using POM.
- Demonstrate real-world QA automation practices.

---

## 🚀 Key Features

| Feature | Description |
|---|---|
| 🔎 Flight Search | Automates searching for available flights |
| 🛫 Flight Selection | Validates flight selection workflow |
| 🎫 Booking Flow | Automates important booking steps |
| ✅ Assertions | Verifies expected vs actual results |
| 📸 Screenshots | Captures screenshots on failures |
| 🐞 Bug Reporting | Records detected failures |
| 📊 Test Reports | Generates TestNG execution reports |
| 🧩 Page Object Model | Separates page logic from test logic |
| ⚙️ Maven | Handles dependencies and project build |
| 🔁 Reusable Tests | Supports scalable test automation |

---

# 🏗️ System Architecture

```text
                    ┌─────────────────────────┐
                    │      Airline Website    │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │   Selenium WebDriver    │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │     Page Objects        │
                    │                         │
                    │ Login / Search / Booking │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │      TestNG Tests       │
                    │                         │
                    │ Assertions & Validation │
                    └────────────┬────────────┘
                                 │
                    ┌────────────┴────────────┐
                    ▼                         ▼
          ┌──────────────────┐      ┌──────────────────┐
          │  TestNG Reports  │      │ Screenshot Capture│
          └──────────────────┘      └─────────┬────────┘
                                              │
                                              ▼
                                    ┌──────────────────┐
                                    │  Bug Reporting   │
                                    └──────────────────┘
