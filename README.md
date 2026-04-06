<!-- HEADER -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A2980,100:26D0CE&height=200&section=header&text=Airline%20Automation%20Testing&fontSize=35&fontColor=ffffff"/>

---

# ✈️ Airline Bug Reporting & Automation Project

## 📌 Overview

This project demonstrates **automation testing of an airline booking system** using Selenium WebDriver.

It simulates real-world QA scenarios such as:

* Login validation
* Flight search
* Booking failures
* Bug reporting with screenshots

---

## 🎯 Features

✔ Automated UI Testing using Selenium
✔ Flight search & booking validation
✔ Login error handling
✔ Screenshot capture on failure 📸
✔ Page Object Model (POM) design

---

## 🛠️ Tech Stack

* Language: Java
* Automation Tool: Selenium WebDriver
* Framework: TestNG
* Build Tool: Maven

---

## 📂 Project Structure

```bash
Airline-Bug-Report/
│── src/
│   ├── test/java/
│   ├── main/java/
│   └── pages/
│── screenshots/
│── pom.xml
│── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/your-username/airline-bug-report.git
cd airline-bug-report
```

---

### 2. Install Dependencies

```bash
mvn clean install
```

---

### 3. Run Tests

```bash
mvn test
```

---

## 🧪 Sample Test Case

**Test:** Login with invalid credentials

**Steps:**

1. Open airline website
2. Enter wrong username/password
3. Click login

**Expected Result:** Error message displayed
**Actual Result:** Login fails / system error

---

## 🐛 Bug Report Example

| Field           | Description                          |
| --------------- | ------------------------------------ |
| Bug ID          | AIR-001                              |
| Title           | Login fails with invalid credentials |
| Severity        | High                                 |
| Priority        | High                                 |
| Steps           | Open → Enter invalid → Click login   |
| Expected Result | Proper error message                 |
| Actual Result   | Error / crash                        |
| Status          | Open                                 |

---

## 📸 Screenshots

👉 Add your screenshots inside `/screenshots` folder

Example:

```
screenshots/login_error.png
```

---

## 📈 Future Improvements

* CI/CD Integration (GitHub Actions)
* Allure Reports
* Parallel Execution
* Cloud Testing (BrowserStack)

---

## 🤝 Contributing

Pull requests are welcome!

---

## 📜 License

MIT License

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A2980,100:26D0CE&height=120&section=footer"/>
