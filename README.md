
# 🧪 SauceDemo - JMeter Performance Testing Project

## 📌 Project Overview

This repository contains a **Performance Testing project** developed for the **SauceDemo website** using **Apache JMeter**.

The project focuses on evaluating application response behavior under concurrent user load, configuring test data, validating responses using assertions, and analyzing test execution results.

---

## 🌐 Application Under Test

**Website:**

https://www.saucedemo.com/

---

## 🎯 Project Objectives

- Perform performance testing using Apache JMeter.
- Evaluate application behavior under concurrent user load.
- Configure HTTP requests and test execution settings.
- Use CSV data for parameterized testing.
- Validate server responses using assertions.
- Analyze response times and test execution results.
- Generate performance testing documentation.

---

## 🛠️ Tools & Technologies Used

| Tool / Technology | Purpose |
|---|---|
| Apache JMeter | Performance Testing |
| CSV Data Set Config | Test Data Management |
| HTTP Request | Sending HTTP Requests |
| Response Assertion | Response Validation |
| Size Assertion | Response Size Validation |
| Duration Assertion | Response Time Validation |
| View Results Tree | Response Inspection |
| Summary Report | Performance Results |
| Canva | Project Documentation |

---

## ⚙️ Test Configuration

| Configuration | Value |
|---|---|
| Number of Threads (Users) | 10 |
| Ramp-Up Period | 5 seconds |
| Loop Count | 1 |
| Protocol | HTTPS |
| Server | www.saucedemo.com |
| Test Data | CSV Data Set Config |

---

## 🧩 JMeter Components Used

### 🔹 HTTP Request Defaults

- Configure the protocol and server name.
- Set the default application path.
- Reuse common HTTP request settings.

### 🔹 CSV Data Set Config

- Load test data from a CSV file.
- Configure username and password variables.
- Use CSV data during test execution.

### 🔹 HTTP Header Manager

- Configure HTTP request headers when required.
- Maintain request header settings.

### 🔹 Uniform Random Timer

- Add a random delay between requests.
- Simulate variations in user request timing.

### 🔹 HTTP Requests

- Login HTTP Request
- Browse Product HTTP Request

---

## ✅ Assertions Used

### 🔹 Response Assertion

Used to validate the response content according to the configured assertion conditions.

### 🔹 Size Assertion

Used to validate the response size in bytes.

### 🔹 Duration Assertion

Used to validate whether the response is completed within the configured time limit.

---

## 📊 Results & Reporting

The following JMeter components were used to inspect and analyze test execution:

- View Results Tree
- Summary Report
- Assertion Results

These components help review request responses, response times, and assertion outcomes.

---

## 📂 Project Structure

```text
JMeter-Performance-Testing
│
├── TEST.jmx
│
├── Book1.csv
│
├──SauceDemo_Performance_Testing.pdf
│
└── README.md
```

---

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Install Apache JMeter.
3. Open `TEST.jmx` in Apache JMeter.
4. Verify the CSV file path in CSV Data Set Config.
5. Check the Thread Group settings.
6. Review the configured HTTP Requests and assertions.
7. Run the test plan.
8. Review the test results using the available listeners.

---

## 📸 Project Documentation

The project documentation includes screenshots of:

- JMeter Test Plan
- HTTP Request Defaults
- CSV Data Set Config
- HTTP Header Manager
- Uniform Random Timer
- HTTP Requests
- Response Assertion
- Size Assertion
- Duration Assertion
- View Results Tree
- Summary Report
- Assertion Results

---

## 💡 Skills Demonstrated

- Apache JMeter
- Performance Testing
- Load Testing Fundamentals
- HTTP Request Configuration
- CSV Data-Driven Testing
- Response Validation
- Assertion Configuration
- Test Result Analysis
- Test Plan Design
- Performance Testing Documentation

---

## 🚀 Future Enhancements

- Increase concurrent user load.
- Add additional performance test scenarios.
- Improve test data parameterization.
- Add more detailed performance metrics.
- Generate HTML performance reports.
- Compare results across different load levels.
- Integrate JMeter testing into a CI/CD pipeline.

---

## 👨‍💻 Author

**Gokul S**

Aspiring Software Test Engineer with hands-on experience in Manual Testing, Selenium Automation, and Apache JMeter Performance Testing.

---

## ⭐ About This Project

This project is part of my Software Testing portfolio and demonstrates practical experience in designing and executing a performance test plan using Apache JMeter.

The project includes test configuration, data management, assertions, and test result analysis for a web application.
