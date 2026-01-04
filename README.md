# 📅 Propine_DateParser

**Propine_DateParser** is a Java-based automation and utility framework designed to **parse, normalize, and validate multiple date formats** reliably.  
The project demonstrates clean automation architecture, robust test coverage, and industry-standard tooling using **Maven, TestNG, Log4j, and Extent Reports**.

This repository showcases best practices in **test automation, framework design, and quality engineering**.

---

## 🎯 Purpose

Applications frequently receive dates in **multiple inconsistent formats**, which can cause parsing errors, data corruption, or unexpected behavior.

This framework ensures:
- Accurate date parsing across formats
- Validation of edge cases and invalid inputs
- Automated verification through structured test suites
- Maintainable and extensible automation design

---

## 🚀 Key Features

✔ Supports parsing of multiple date formats  
✔ Centralized parsing logic with reusable utilities  
✔ Automated test execution using TestNG  
✔ Detailed execution logs using Log4j  
✔ Rich HTML test reports via Extent Reports  
✔ Maven-based build for CI/CD readiness  
✔ Scalable folder structure following automation best practices  

---

## 🧱 Project Structure

Propine_DateParser/
├── .settings/ # IDE-specific settings
├── Configuration/ # Framework configuration files
├── Drivers/ # External drivers/utilities (if applicable)
├── Screenshots/ # Failure screenshots (if enabled)
├── logs/ # Execution logs
├── src/
│ ├── main/java/ # Core date parser & utility logic
│ └── test/java/ # Automated test cases
├── target/ # Build artifacts & reports
├── pom.xml # Maven dependencies & build config
├── TestNG.xml # Test suite definition
├── extent-config.xml # Extent report configuration
├── log4j.properties # Logging configuration
└── README.md

---

## 🛠️ Technology Stack

- **Language:** Java  
- **Build Tool:** Maven  
- **Test Framework:** TestNG  
- **Logging:** Log4j  
- **Reporting:** Extent Reports  
- **Version Control:** Git & GitHub  

---

## 📦 Prerequisites

Ensure the following are installed before running the project:

- Java 8 or higher
- Maven 3.6+
- Git
- IDE (IntelliJ IDEA / Eclipse recommended)

---

## 🔧 Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ProfessionalTiger/Propine_DateParser.git
cd Propine_DateParser

**Build the Project**
mvn clean install

Framework Design Overview
📌 Date Parsing Logic

Centralized parsing utilities handle various date formats

Ensures normalization into a standard format

Gracefully handles invalid and edge-case inputs

📌 Test Automation Design

Clear separation between test logic and utilities

Configurable execution via TestNG XML

Easily extendable for new formats or test cases

**CI/CD Ready**

This project is structured to integrate easily with:

Jenkins

GitHub Actions

GitLab CI

Azure DevOps

Simply trigger mvn clean test in your pipeline.

**Contact**

Author: Aamir Saleem
Role: QA Automation / Quality Engineering Leader

