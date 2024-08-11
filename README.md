# BDD Cucumber Automation Framework

## Introduction
This repository contains a Behavior-Driven Development (BDD) automation framework using Cucumber. The framework is designed to create automated test scripts in a natural language format, making it easy for non-technical stakeholders to understand and contribute to the testing process.

## Features
- **BDD with Cucumber:** Write test cases in plain English using Gherkin syntax.
- **Scalable Framework:** Easily add new test cases and features.
- **Modular Design:** Separate concerns such as test logic, page objects, and utility functions.
- **Integration with Selenium:** Execute tests across various browsers.
- **Reporting:** Generate detailed test reports with screenshots for failures.
- **Cross-browser Testing:** Support for running tests on multiple browsers.

## Prerequisites
- Java 17 or above
- Maven
- IDE (IntelliJ IDEA, Eclipse, etc.)
- Browser drivers (e.g., ChromeDriver, EdgeDriver)

## Setup Instructions
1. Clone the repository:
  ```bash
   git clone https://github.com/atharvjuwekar/bdd-cucumber-automation-framework.git
  ```
2. Navigate to project directory:
  ```bash
  cd bdd-cucumber-automation-framework
  ```
3. Install dependencies:
  ```bash
  mvn clean install
  ```
4. Run the tests:
  ```bash
  mvn test
  ```

## Directory Structure
- **src/test/java**: Contains the step definitions and test runners.
- **src/main/java**: Contains the page objects and utility classes.
- **src/test/resources**: Contains the feature files written in Gherkin.

## How to Write a Test
1. Create a feature file in src/test/resources/features.  
2. Write your scenarios using Gherkin syntax.  
3. Create step definitions in src/test/java/stepdefinitions.  
4. Run the tests using the test runner class.

## Reporting
Test reports are generated automatically after each test run and can be found in the **reports/myReports.html** directory.

## Contributing
We welcome contributions to improve the framework. Please adhere to the following steps:  

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

## Contact
Got questions, feedback, or just want to chat about all things tech? I'm all ears!  
Feel free to reach out through any of the following channels:  
📧 Email: [here](atharvjuwekar.aj@gmail.com) – Drop me a line anytime!  
🌐 LinkedIn: [atharvjuwekar](https://linkedin.com/in/atharvjuwekar) – Connect with me for networking and professional insights.  

Looking forward to hearing from you!
