<!-- ✈️ ANIMATED HEADER -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A2980,50:26D0CE,100:00C9FF&height=220&section=header&text=Airline%20Bug%20Reporting%20System&fontSize=38&fontAlignY=35&animation=fadeIn"/>

<!-- ✈️ TYPING ANIMATION -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=00C9FF&center=true&vCenter=true&width=700&lines=Airline+Booking+Automation;Bug+Reporting+System;QA+Testing+Project;Selenium+WebDriver+Framework" />
</p>

---

# ✈️ Airline Bug Reporting & Automation Testing Project

## 📌 Overview

This project simulates a **real-world airline booking system testing workflow** using Selenium.

It automates key user actions like:

* Flight search ✈️
* Booking process 🧾
* Login validation 🔐

👉 Along with **automated bug detection, screenshot capture, and reporting**

---

## 🎯 Why This Project?

✔ Real-world airline booking scenario
✔ Demonstrates **QA + Automation + Debugging skills**
✔ Covers **critical user flows (login, search, booking)**
✔ Strong portfolio project for **SDET / QA / Data roles**

---

## 🎥 Demo

![Demo](screenshots/demo.gif)

---

## 🧪 Test Execution Flow

<p align="center">
  <img src="https://img.shields.io/badge/Open%20Airline%20Website-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Search%20Flight-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Enter%20Invalid%20Details-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Booking%20Fails-black?style=for-the-badge"/>
</p>

---

## 🐛 Bug Reporting Workflow

<img src="https://miro.medium.com/max/1400/1*QK5xN4hZlKp2k1pG1Hj6VQ.png" width="100%"/>

---

## 🚀 Features

✔ Automated airline booking testing
✔ Flight search validation
✔ Login & payment error testing
✔ Screenshot capture on failure 📸
✔ Page Object Model (POM) design
✔ Structured bug reports

---

## 🛠️ Tech Stack

* Language: Java / Python
* Automation Tool: Selenium WebDriver
* Framework: TestNG / PyTest
* Build Tool: Maven
* Drivers: ChromeDriver / GeckoDriver

---

## 📂 Project Structure

```bash
Airline-Bug-Report/
│── src/
│   ├── tests/
│   │   ├── loginTest
│   │   ├── flightSearchTest
│   │   └── bookingTest
│   ├── pages/
│   │   ├── LoginPage
│   │   ├── SearchPage
│   │   └── BookingPage
│   └── utils/
│── reports/
│── screenshots/
│── README.md
```

---

## ⚙️ Setup Instructions

```bash
git clone https://github.com/your-username/airline-bug-report.git
cd airline-bug-report
```

### Install Dependencies

#### Python:

```bash
pip install -r requirements.txt
```

#### Java:

```bash
mvn clean install
```

---

## ▶️ Run Tests

```bash
mvn test
```

OR

```bash
pytest tests/
```

---

## 🧪 Sample Test Case

**Test:** Flight Booking Failure

**Steps:**

1. Open airline website
2. Search flight Delhi → Mumbai
3. Enter invalid passenger details
4. Proceed to booking

**Expected Result:** Proper validation message
**Actual Result:** Booking crashes ❌

---

## 🐛 Bug Report Example

| Field           | Description                                |
| --------------- | ------------------------------------------ |
| Bug ID          | AIR-001                                    |
| Title           | Booking fails on invalid passenger details |
| Severity        | Critical                                   |
| Priority        | High                                       |
| Module          | Booking System                             |
| Steps           | Search → Enter invalid data → Book         |
| Expected Result | Error message shown                        |
| Actual Result   | System crash                               |
| Status          | Open                                       |

---

## 📸 Screenshots

Captured automatically in `/screenshots`

<p align="center">
  <img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="300"/>
</p>

---

## 📈 Future Improvements

* 🔄 CI/CD (GitHub Actions)
* 📊 Allure Reporting
* ⚡ Parallel Testing
* ☁️ Cloud Testing (BrowserStack)

---

## 🤝 Contributing

Pull requests are welcome 🚀

---

## 📜 License

MIT License

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
