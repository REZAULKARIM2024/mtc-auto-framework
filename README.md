# MultiCart Automation – BDD Cucumber Test Automation Framework

A scalable and maintainable UI automation framework built for the MultiCart demo e-commerce application. This project showcases modern QA automation practices using Behavior-Driven Development (BDD), focusing on real-world user scenarios, clean design, and reusable components.

---

## 🚀 Overview

**MultiCart Automation Framework** is designed to automate key workflows of a multi-vendor e-commerce platform. It simulates real user behavior such as browsing products, managing carts, and validating UI elements across multiple pages.

🔗 **Application Under Test:**
https://www.demo.iscripts.com/multicart/demo/index.php

---

## 🛠️ Tech Stack

* **Language:** Java
* **Automation Tool:** Selenium WebDriver
* **BDD Framework:** Cucumber (Gherkin)
* **Test Runner:** TestNG
* **Build Tool:** Maven
* **IDE:** Eclipse / IntelliJ

---

## 📁 Project Structure

```id="c3w8d2"
project-root/
│
├── src/test/java/
│   ├── features/        # Gherkin feature files
│   ├── steps/           # Step definition classes
│   ├── hooks/           # Setup & teardown (Before/After hooks)
│   └── runner/          # Test runner classes
│
├── src/main/java/
│   └── pages/           # Page Object Model (POM) classes
│
├── testng.xml           # TestNG suite configuration
├── pom.xml              # Maven dependencies and plugins
└── README.md            # Project documentation
```

---

## 🎯 Test Coverage

This framework covers essential functionalities of a multi-vendor e-commerce platform:

* 🔐 **Authentication**

  * User login and logout scenarios
* 🛍️ **Product Browsing**

  * View product listings and details
* 🛒 **Cart Management**

  * Add/remove products
  * Update quantities
  * Validate cart totals
* 🏬 **Multi-Vendor Flows**

  * Interacting with different sellers/vendors
* 🔎 **Search & Navigation**

  * Product search and category navigation
* 🎯 **UI Validation**

  * Element visibility, text assertions, and layout checks

---

## ⚙️ Framework Highlights

* ✔️ BDD implementation with Cucumber (Gherkin syntax)
* ✔️ Page Object Model (POM) for clean and maintainable code
* ✔️ Reusable step definitions and hooks
* ✔️ Parameterized locators for dynamic elements
* ✔️ TestNG integration for execution control
* ✔️ Maven for dependency and build management

---

## ▶️ Running the Tests

### Using Maven

```bash id="q6f7a1"
mvn clean test
```

### Using TestNG Suite

```bash id="1x9n3p"
mvn test -DsuiteXmlFile=testng.xml
```

### Using IDE (Eclipse / IntelliJ)

* Right-click on the TestNG runner class
* Select **Run As → TestNG Test**

---

## 📌 Prerequisites

Ensure the following are installed:

* Java (JDK 8 or higher)
* Maven
* Eclipse / IntelliJ IDE
* Browser drivers (e.g., ChromeDriver)

---

## 📈 Future Enhancements

* Add reporting (Extent Reports / Allure Reports)
* Integrate CI/CD (Jenkins / GitHub Actions)
* Enable parallel test execution
* Add cross-browser testing
* Implement data-driven testing (Excel/JSON)
* Cloud execution (BrowserStack / Sauce Labs)

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork the repository and submit pull requests.

---

## 👨‍💻 Author

**Rezaul Karim**
Software QA Engineer | Automation & Manual Testing

---

## 📄 Summary

This project demonstrates a real-world automation framework for a multi-vendor e-commerce platform, highlighting strong QA engineering skills, scalable design patterns, and industry best practices in UI automation and BDD.

---
