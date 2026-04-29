# Enterprise Risk Register

| Risk ID | Risk Description                                 | Impact   | Likelihood | Risk Level | Owner               | Mitigation Strategy                          |
| ------- | ------------------------------------------------ | -------- | ---------- | ---------- | ------------------- | -------------------------------------------- |
| R-001   | Fake login attempt using stolen credentials      | High     | Medium     | High       | Security Team       | MFA, password policy, account lockout        |
| R-002   | API request tampering and malicious payloads     | High     | High       | Critical   | Application Team    | Input validation, API Gateway protection     |
| R-003   | User activity not properly logged                | Medium   | Medium     | Medium     | SOC Team            | Centralised logging and audit trails         |
| R-004   | Sensitive data exposure from API or database     | Critical | Medium     | High       | Database Team       | Encryption using AWS KMS and access controls |
| R-005   | Denial of Service attack against web application | High     | Medium     | High       | Infrastructure Team | AWS WAF, rate limiting, autoscaling          |
| R-006   | Privilege escalation through admin accounts      | Critical | Medium     | Critical   | IAM Team            | Least privilege IAM, RBAC, MFA               |
| R-007   | Database queried without authorisation           | Critical | Low        | High       | Database Team       | Database monitoring and access restrictions  |

