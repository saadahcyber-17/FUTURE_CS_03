# API Security Risk Analysis

## Overview

This repository contains an **API Security Risk Analysis** conducted against the **JSONPlaceholder** public REST API. The assessment was performed as part of a cybersecurity internship project to demonstrate the methodology used by security analysts and application security consultants when evaluating API security.

The objective of this project was to identify potential API security risks through a structured, **read-only assessment** without exploiting vulnerabilities or performing any unauthorized testing.

---

## Objectives

* Analyze a public REST API using industry-standard tools.
* Evaluate common API security controls.
* Identify potential security risks.
* Assess the business impact of identified findings.
* Provide practical remediation recommendations.
* Document the assessment in a professional security report.

---

## Target API

**API:** JSONPlaceholder

**Base URL:**

```text
https://jsonplaceholder.typicode.com
```

JSONPlaceholder is a public demonstration API designed for learning, development, and testing purposes.

---

## Scope of Assessment

The assessment included:

* API documentation review
* Endpoint enumeration
* HTTP request and response analysis
* Authentication review
* Authorization assessment
* Response data analysis
* HTTP header inspection
* Input handling observation
* Risk classification
* Security recommendations

The assessment was limited to **read-only testing** and followed ethical security testing practices.

---

## Tools Used

* Postman
* Insomnia
* Browser Developer Tools
* Google Docs / Microsoft Word
* Git & GitHub

---

## Methodology

The assessment followed a structured methodology based on the **OWASP API Security Top 10 (2023)**.

1. Reviewed API documentation.
2. Enumerated available endpoints.
3. Tested endpoints using Postman and Insomnia.
4. Analyzed HTTP requests and responses.
5. Reviewed authentication and authorization mechanisms.
6. Inspected HTTP response headers.
7. Evaluated response data exposure.
8. Observed input handling.
9. Classified identified risks.
10. Documented remediation recommendations.

---

## Key Findings

| Finding                                          | Severity |
| ------------------------------------------------ | -------- |
| Unauthenticated Access to Public API Endpoints   | Medium   |
| Excessive Data Exposure in API Responses         | Medium   |
| Potential Authorization Control Weakness         | Medium   |
| Information Disclosure via HTTP Response Headers | Low      |

> **Note:** JSONPlaceholder is intentionally designed as a public demonstration API. The observations documented in this assessment illustrate security considerations that would be significant if similar behavior were identified in a production environment.

---

## Repository Structure

```text
API-Security-Risk-Analysis/
│
├── README.md
├── Report/
│   └── API_Security_Risk_Analysis.pdf
│
├── Screenshots/
│   ├── screenshot1.png
│   ├── screenshot2.png
│   ├── screenshot3.png
│   └── screenshot4.png
│
└── Postman Collection/
    └── API_Security_Assessment.postman_collection.json


```

---

## Learning Outcomes

Through this project, I gained practical experience in:

* API security assessment methodology
* REST API analysis
* HTTP request and response inspection
* Authentication and authorization review
* OWASP API Security Top 10
* Security risk classification
* Technical report writing
* Business impact analysis
* Security recommendation development

---

## Ethical Statement

This assessment was conducted solely against a publicly available demonstration API intended for testing and educational purposes. All testing was limited to authorized, read-only requests. No exploitation, denial-of-service testing, authentication bypass, or attempts to compromise systems were performed.

---

## References

* OWASP API Security Top 10 (2023)
* JSONPlaceholder Documentation
* Postman Documentation
* Insomnia Documentation

---

## Disclaimer

This repository is intended for educational and portfolio purposes only. The findings documented in this report are based on observations made during the assessment of a public demonstration API and should not be interpreted as vulnerabilities affecting production systems.
