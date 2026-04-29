# Project 21 – STRIDE Threat Modelling Foundation Lab

## Overview

This project demonstrates a foundational enterprise STRIDE threat modelling exercise for a secure web application architecture. The objective of the lab is to identify, analyse, and mitigate security threats across user authentication, application communication, API interactions, and database operations.

The project follows a structured security architecture approach aligned with:

* STRIDE threat modelling methodology
* Secure-by-design principles
* Enterprise risk assessment practices
* Cloud security governance concepts
* AWS-native mitigation strategies

---

# Objectives

The objectives of this project are:

* Understand trust boundaries within distributed systems
* Analyse secure data flows between system components
* Identify threats using the STRIDE framework
* Create an enterprise risk register
* Define mitigation strategies using modern cloud security controls
* Document architecture and governance decisions professionally

---

# Architecture Components

The secure web application architecture includes:

| Component       | Purpose                                        |
| --------------- | ---------------------------------------------- |
| User            | External client accessing the application      |
| Web Application | Frontend application handling user interaction |
| API Server      | Backend processing and business logic          |
| Database        | Secure storage of application data             |

---

# Data Flow Analysis

The following communication paths were analysed:

1. User → Web Application (HTTPS Login Request)
2. Web Application → API Server (API Request)
3. API Server → Database (SQL Query)
4. Database → Application Response

Trust boundaries and database protection zones were identified to determine where security validation and monitoring are required.

---

# STRIDE Threat Analysis

The following STRIDE categories were analysed:

| STRIDE Category        | Example Threat             |
| ---------------------- | -------------------------- |
| Spoofing               | Stolen user credentials    |
| Tampering              | Modified API requests      |
| Repudiation            | Missing audit logs         |
| Information Disclosure | Sensitive data exposure    |
| Denial of Service      | Excessive traffic flooding |
| Elevation of Privilege | Unauthorised admin access  |

---

# Enterprise Risk Management

A formal enterprise risk register was created to document:

* Risk IDs
* Impact levels
* Likelihood ratings
* Ownership responsibilities
* Mitigation strategies

This simulates a real-world governance and security architecture workflow.

---

# Security Mitigations

The following mitigation controls were identified:

* Multi-Factor Authentication (MFA)
* Strong password policies
* TLS encryption
* API validation
* AWS WAF protection
* Rate limiting
* Least privilege IAM
* Centralised audit logging
* Database encryption
* Access control enforcement

---

# Tools Used

| Tool                   | Purpose                              |
| ---------------------- | ------------------------------------ |
| Visual Studio Code     | Documentation and project management |
| Draw.io / diagrams.net | Architecture and DFD creation        |
| Markdown               | Technical documentation              |
| STRIDE                 | Threat modelling methodology         |

---

# Evidence Collected

The following evidence was captured during the project:

* Project structure
* Secure architecture diagram
* Data Flow Diagram (DFD)
* Trust boundary analysis
* STRIDE threat table
* Enterprise risk register

---

# Skills Demonstrated

This project demonstrates:

* Threat modelling
* Security architecture analysis
* Enterprise risk assessment
* Secure system design
* STRIDE methodology
* Governance documentation
* Cloud security thinking
* Technical communication

---

# Business Value

This project demonstrates the ability to:

* Analyse secure architectures
* Identify enterprise threats
* Document security risks professionally
* Apply structured threat modelling techniques
* Align security controls to business risk reduction

---

# Author

Dr. Ime Ben
AWS Cloud Security Architect
Cloud Security | Threat Modelling | DevSecOps | Enterprise Security Architecture

