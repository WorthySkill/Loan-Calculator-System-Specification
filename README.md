# Loan Calculator System - Enterprise Architecture & Software Design Specification

A comprehensive software engineering blueprint and full system lifecycle specification for an enterprise-level Loan Calculator and Intelligent Strategic Advisory platform. This portfolio showcases advanced system analysis, relational database schema engineering, object-oriented design patterns, unified modeling language (UML) structural mappings, and end-to-end testing strategies.

## 🧠 System Innovations & Core Features

### 1. Intelligent Strategic Advisory Engine
Unlike passive financial calculators that compute raw numbers, this system incorporates a rule-based inference engine. It analyzes a user's business profile (e.g., Startup vs. Enterprise) and corporate financial goals (e.g., Working Capital, Expansion, Real Estate) to dynamically recommend the optimal financial instrument (e.g., Equipment Financing, Working Capital Loan, or Commercial Mortgage).

### 2. Multi-Layered Architecture & MVC Separation
Designed utilizing a 4-Tier Layered Architecture coupled with the Model-View-Controller (MVC) structural pattern to achieve tight decoupling of dependencies:
* **Presentation & Application Layer:** Handles friendly graphical user interface (GUI) interactions, session state tracking, and secure credential routing.
* **Core Business Logic Layer:** Coordinates the core mathematical amortization engine and dynamic loan factory generation modules.
* **System Support Layer:** Facilitates thread pool management, database routing, and secure external network connection services.

### 3. Financial Precision & Penny-Drift Mitigation
Addresses floating-point precision limitations inherent in standard binary hardware types (`double` and `float`) by enforcing a strict high-precision decimal allocation model:
* **Application Level:** Employs explicit object-oriented financial libraries (`java.math.BigDecimal`) for math execution.
* **Database Level:** Provisions column types using strict `DECIMAL(19, 4)` schemas to maintain perfect balance truncation across a rolling 30-year amortization framework.

## 📊 Unified Modeling Language (UML) Specifications
The complete operational flow of the ecosystem is formally modeled using structural and behavioral engineering maps:
* **Class Diagram:** Models structural domain objects (`Loan`, `Payment`, `AmortizationSchedule`, `UserInterface`) demonstrating high encapsulation, strict data validation boundaries, and 1-to-many operational dependencies.
* **Sequence Diagram:** Outlines clear transactional boundaries between the View layer, `LoanController` interface, and business model objects, complete with data validation routing parameters.
* **Activity Diagram:** Tracks the explicit execution path of the Rule-Based Inference Advisory Loop to map profile parameters to precise corporate asset recommendations.

## 🛠️ Planned Enterprise Technology Stack
* **Backend Frameworks:** Python (PyTest) / Java (Spring Boot / JUnit)
* **Frontend Web & Mobile App:** React Native (JavaScript/Dart) / JavaSwing GUI
* **Database Management:** Relational SQL (MySQL / Microsoft SQL Server)
* **Validation Suite Tools:** Selenium (GUI Tracking), Postman (REST API Validation), Apache JMeter (10,000 Concurrent User Load Testing), OWASP ZAP (Security Auditing)

## 📁 Repository Structure
* `Loan_Calculator_Complete_Blueprint.pdf` - The complete, publication-ready architectural design specification document.
* `UML-Diagrams/` - Dedicated directory storing structural component graphs, sequence tracking models, and state charts.
