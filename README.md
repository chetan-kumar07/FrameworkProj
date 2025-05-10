# 📚 Test Automation Framework

This project is a comprehensive **Selenium-based test automation framework** built using **Java**, **TestNG**, and **Cucumber BDD**. It follows best practices such as the **Page Object Model (POM)** and integrates industry-standard tools to ensure scalability, reusability, and maintainability.

---

## 🔧 Key Features

- **Maven** for build management  
- **TestNG** for test execution and grouping  
- **Selenium WebDriver** for browser automation  
- **WebDriverManager** for driver management  
- **Page Object Model & Page Factory** for clean test architecture  
- **Log4j2** for logging  
- **ExtentReports** for detailed test reporting  
- **Apache Commons IO** for file operations  
- **Data-driven testing** using TestNG `@DataProvider`  
- **Parallel execution** with TestNG configuration  
- **Screenshot capture** on test failures via Listeners  
- **Cucumber BDD** for behavior-driven development  

---

## 📁 Project Structure Highlights

### `src/main/java`

- `resources` – Configuration files (`data.properties`, `log4j2.xml`)  
- `base` – Base classes and browser setup logic  
- `pageobjects` – Page classes encapsulating web elements and interactions  
- `utilities` – Utility classes (e.g., Extent Report integration)  
- `listeners` – TestNG Listeners for logging, screenshot capture, and report generation  

### `src/test/java`

- `tests` – Test classes written using TestNG  
- `features` – Gherkin feature files for Cucumber  
- `stepdefinitions` – Step definition classes for BDD scenarios  
- `runner` – Cucumber TestNG runner for executing BDD tests  

---

## 🚀 Execution

- Run tests via **TestNG XML** or **Cucumber TestNG runner**  
- Execute from the command line with Maven:  
  ```bash
  mvn test
