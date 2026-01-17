# OWASP Juice Shop – XSS Vulnerability Report

## Objective
To study and demonstrate a Cross-Site Scripting (XSS) vulnerability
using OWASP Juice Shop.

## Vulnerability Type
Cross-Site Scripting (XSS)

## Payload Used
```html
<script>alert('XSS')</script>
## Observation
The injected script executes in the browser, indicating that user input
is not properly sanitized.

## Impact
- Execution of malicious JavaScript
- Cookie and session theft
- User redirection or phishing attacks

## Mitigation
- Validate and sanitize all user inputs
- Encode output before rendering
- Implement Content Security Policy (CSP)

## Conclusion
This project demonstrates how Cross-Site Scripting (XSS) vulnerabilities
can occur due to improper input handling in web applications.
