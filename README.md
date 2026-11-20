# SWYNEX Security Assessment Report

Final report for **Task 4** of the SWYNEX Technologies Cyber Security Internship.
It combines the findings from my earlier defensive security tasks into one professional assessment.

## Contents

- [`Security Assessment Report.pdf`](./security-assessment-report.pdf) - the full report

## Report Sections

1. Executive Summary
2. Methodology
3. Findings and Risk Ratings
4. Detailed Findings with Evidence
5. Remediation Recommendations
6. Conclusion

## Summary of Findings

| ID | Finding | Severity |
|----|---------|----------|
| F1 | SQL injection: login bypass | Critical |
| F2 | Broken access control (IDOR): basket enumeration | High |
| F3 | Sensitive data exposure: public /ftp directory | High |
| F4 | Cross-site scripting (XSS) in search field | Medium |
| F5 | Missing security headers and permissive CORS | Low to Medium |
| F6 | Unencrypted HTTP traffic | Medium |
| F7 | Visible DNS queries | Low |
| F8 | TLS traffic and Expert Information warnings | Informational |

## Source Tasks

- [Task 1: Security Fundamentals Assessment](https://github.com/hannah-zaky/Task-1-Security-Fundamentals-Assessment)
- [Task 2: Network Security Analysis](https://github.com/hannah-zaky/SWYNEX-Network-Security-Analysis)
- [Task 3: Web Security Review](https://github.com/hannah-zaky/SWYNEX-Web-Security-Review)

## Tools Used

Wireshark, Burp Suite Community Edition, Firefox DevTools, Kali Linux, Docker, OWASP Juice Shop.

## Disclaimer

All testing was performed only in authorized lab environments against an intentionally vulnerable training application (OWASP Juice Shop) and my own virtual machine. No third-party or production systems were tested. Credentials and sensitive information were removed or redacted.
