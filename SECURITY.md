# 🛡️ Security Policy

## Supported Versions

We actively release security patches and updates for the following versions of NutriScan:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

---

## 🔒 Reporting a Vulnerability

The NutriScan team takes the security of our application and user data seriously. If you discover a security vulnerability, please **do not** open a public issue.

Instead, please report vulnerabilities privately by following these steps:

1. Send an email to **harshitkumar@example.com** with details of the vulnerability.
2. Include a description of the issue, steps to reproduce, and potential impact.
3. We will acknowledge receipt of your report within 48 hours and work on a fix promptly.

---

## 🛡️ Security Best Practices in NutriScan

- **Environment Isolation**: API keys and database credentials must be configured via environment variables (`.env`) and never committed to version control.
- **Input Sanitization**: Query parameter sanitization on Express.js routes to prevent Injection attacks.
- **Rate Limiting**: Protection on public food lookup routes to prevent API abuse.

Thank you for keeping **NutriScan** safe for everyone!
