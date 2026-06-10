# 7zip-security-assessment
Comprehensive security assessment of 7-Zip including threat modeling, CVE root-cause analysis, static code review, risk assessment, and secure software engineering recommendations.

# 7-Zip Security Assessment

## Overview

This repository contains a comprehensive security assessment of **7-Zip**, conducted as part of a Secure Software Engineering study. The assessment evaluates the security posture of the application through threat modeling, historical vulnerability analysis, static code analysis, and risk assessment.

The objective was to identify potential security weaknesses, analyze real-world vulnerabilities, and recommend secure software engineering practices that could improve the resilience of the application.

---

## Assessment Scope

The assessment covered the following areas:

* Software architecture review
* Threat modeling using STRIDE
* Historical CVE analysis
* Vulnerability trend analysis
* Source code commit review
* Static Application Security Testing (SAST)
* Risk assessment
* Security recommendations

---

## Tools Used

| Tool                           | Purpose                            |
| ------------------------------ | ---------------------------------- |
| Microsoft Threat Modeling Tool | STRIDE-based threat modeling       |
| Snyk Code                      | Static code analysis               |
| SonarQube                      | Code quality and security analysis |
| Semgrep                        | Secure coding pattern detection    |
| CVE Database                   | Historical vulnerability research  |

---

## Key Activities

### Threat Modeling

A STRIDE-based threat model was developed to identify potential threats affecting:

* Authentication mechanisms
* File extraction processes
* User interaction components
* Data handling workflows
* System integration points

### Vulnerability Analysis

Historical Common Vulnerabilities and Exposures (CVEs) affecting 7-Zip were analyzed to identify recurring security weaknesses and root causes.

### Static Code Analysis

Security-focused code reviews were conducted using multiple static analysis tools to identify:

* Input validation weaknesses
* Memory safety concerns
* Insecure coding patterns
* Potential attack surfaces

### Risk Assessment

Identified threats and vulnerabilities were evaluated based on:

* Likelihood
* Impact
* Exploitability
* Business risk

---

## Security Domains Covered

* Application Security
* Secure Software Engineering
* Threat Modeling
* Vulnerability Assessment
* Static Analysis
* Secure Development Lifecycle (SDLC)
* Risk Management

---

## Repository Structure

```text
7zip-security-assessment
│
├── README.md
│
├── report
│   └── 7Zip_Security_Assessment.pdf
│
├── diagrams
│   ├── threat-model.png
│   ├── architecture-overview.png
│   └── risk-matrix.png
│
├── screenshots
│   ├── snyk-analysis.png
│   ├── sonarqube-analysis.png
│   └── semgrep-analysis.png
│
└── references
```

---

## Key Learning Outcomes

This project strengthened practical knowledge in:

* Threat Modeling (STRIDE)
* Secure Software Development Lifecycle (SSDLC)
* Vulnerability Research
* CVE Analysis
* Static Application Security Testing (SAST)
* Security Architecture Review
* Risk Assessment Methodologies

---

## Report

The complete assessment report is available in:

```text
report/7Zip_Security_Assessment.pdf
```

---

## Disclaimer

This repository is intended for educational and research purposes. All findings are based on publicly available information, security analysis methodologies, and academic research activities.

---

## Author

**Tharusha Dilshan**

Cyber Security Undergraduate
Sri Lanka Institute of Information Technology (SLIIT)

* LinkedIn: https://linkedin.com/in/tharusha-dilshan-225b12315
* GitHub: https://github.com/TharushaThilakarathna

---

## License

This project is released for educational and portfolio purposes.
