📘 Library Management Web Application – Automated Testing Suite
📊 Build Status | 📄 License: MIT
🔗 Tech Stack: Java · Selenium · TestNG · Cucumber · Maven

This project is a well-structured automation framework developed to test the user interface of a Library Management System. Built using Java, Selenium WebDriver, TestNG, and Cucumber (BDD), it enables consistent, scalable, and maintainable UI test coverage using a modular and behavior-driven approach.

⚙️ Technology Stack
🧑‍💻 Language: Java

🧪 Automation Tools: Selenium WebDriver, TestNG, Cucumber (BDD)

📦 Build Tool: Maven

🔁 Testing Strategy: Behavior Driven Development (BDD)

📊 Data Handling: Hardcoded input + limited Data-Driven Testing via Excel

📐 Design Model: Custom modular pattern (no PageFactory used)

🗂️ Project Structure Overview
Maven-based Java project with dependencies managed through pom.xml

Test scenarios described using .feature files written in Gherkin

Execution configured via testng.xml and TestRunner.java

Test logic implemented through modular Java classes

Reports auto-generated post execution using reporting utilities

Minimal data-driven testing using Excel and utility classes

🔁 Key Reusable Components
🧰 Hooks.java
Manages browser lifecycle via Cucumber hooks (@Before, @After)

Captures failure screenshots automatically

Sets up test environment and global configurations

🚀 TestRunner.java
Combines Cucumber with TestNG for execution

Defines feature paths, step definitions, and tags for filtering

Supports multi-feature execution and integration with reports

🧑‍🤝‍🧑 Team Members & Contributions
👤 Om – Framework Setup & Book Management Automation
Established initial Maven project and configured base classes

Developed DriverSetup.java, Hooks.java, and ConfigReader.java

Implemented and tested BookSection.feature and ChatSupport.feature

Created logic for book services and chat modules with corresponding step definitions

👤 MD Rahman – Module Development, Utilities, and Reporting
Worked on Membership, EmailSupport, LibraryCard, and SearchBook features

Designed and implemented relevant .feature files and step definition classes

Built reusable tools: ScreenshotUtil.java, ExcelReader.java

Integrated Extent and Cucumber reports

Handled environment properties and TestRunner.java setup

📋 Agile Documentation
🧾 Product Backlog:
Prioritized list of features and test goals for automation

🗓️ Sprint Backlog:
Iterative task breakdown by module with weekly targets and test status tracking

