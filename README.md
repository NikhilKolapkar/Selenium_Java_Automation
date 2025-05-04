# 🚀 Selenium Java Automation Framework

This is a basic yet powerful automation framework built using **Selenium WebDriver with Java**, following best practices like **Page Object Model (POM)** and **TestNG** for test organization. It is designed to help QA engineers and developers write clean, maintainable, and scalable UI test cases.

---

## 🚀 Features

- ✅ Selenium WebDriver with Java  
- ✅ Page Object Model (POM) structure  
- ✅ TestNG for test execution and assertions  
- ✅ Browser support: Chrome & Firefox  
- ✅ Maven-based build and execution  
- ✅ Basic reporting and logging  
- ✅ Simple configuration using `config.properties`  

---

## 🔧 Tech Stack

- **Java 11+**  
- **Selenium WebDriver**  
- **TestNG**  
- **Maven**  
- **ExtentReports** (for reporting)  
- **Log4j** (for logging)  
- **GitHub Actions** (for CI - optional)  

---

## ✅ What This Project Covers

- Browser automation using Selenium WebDriver  
- Modular design using Page Object Model  
- Test execution and reporting using TestNG  
- Centralized configuration via `config.properties`  
- Cross-browser support (Chrome and Firefox)  
- Readable logs and assertions for easy debugging  

---

## ✅ Test web page
    http://the-internet.herokuapp.com/  
---

## ✅ Continuous Integration(CI)
  
  - A web hook has been setup with Travis CI for all Push and Pull Requests.
 
 - A web hook has also been setup with Github Actions, and Selenium Tests will execute with [testcontainers](https://www.testcontainers.org/) during CI.
   
---
## ✅ Testcontainers
  
  - Tests "SeleniumContainerTest" will execute Selenium test in a docker container.  In order to execute this test using a testcontainer
    you must install docker, and also have docker running before test execution.

 -  for more information: https://www.testcontainers.org/
   
---

## 📁 Project Structure

```bash
├── src
│   ├── main
│   │   ├── java
│   │   │   └── pages              # Page Object classes
│   │   │   └── utilities          # Utility/helper methods
│   │   └── resources
│   │       └── logback-test.xml   # XML file
│
│   └── test
│       └── java
│           └── tests             # TestNG test cases
│
├── pom.xml                       # Maven configuration
└── README.md                     # Project overview
