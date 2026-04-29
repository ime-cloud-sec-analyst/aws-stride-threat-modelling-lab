# STRIDE Analysis Table

| Component       | Threat                                          | STRIDE Type            | Risk     | Mitigation                                                |
| --------------- | ----------------------------------------------- | ---------------------- | -------- | --------------------------------------------------------- |
| User Login      | Fake login attempt using stolen credentials     | Spoofing               | High     | MFA, strong password policy, account lockout              |
| HTTPS Request   | Request modified in transit or replayed         | Tampering              | High     | TLS, request validation, anti-replay controls             |
| Web Application | User actions not properly logged                | Repudiation            | Medium   | Centralised logging, audit trails, timestamped events     |
| API Server      | API exposes sensitive user data                 | Information Disclosure | High     | Authentication, authorisation, least privilege access     |
| Web Application | Excessive traffic floods the service            | Denial of Service      | Medium   | AWS WAF, rate limiting, autoscaling                       |
| Admin Access    | User gains admin privilege without approval     | Elevation of Privilege | Critical | Least privilege IAM, MFA, role-based access control       |
| Database        | Sensitive records exposed or queried improperly | Information Disclosure | Critical | Encryption, access control, database audit logging        |
| API Request     | Malicious input sent to backend API             | Tampering              | High     | Input validation, schema validation, API Gateway controls |

