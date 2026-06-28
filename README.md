# cs-305-project-one
Secure REST API vulnerability assessment and refactoring project using OWASP Dependency-Check, input validation, and role-based authorization.

Artemis Financial is a consulting company that develops individualized financial plans for customers. It sought to protect client data and financial information by securing its RESTful web API through manual code review and static testing with OWASP Dependency-Check.

Manual code inspection revealed several vulnerabilities that needed to be fixed, including stack traces printed to the console/logs, hardcoded sensitive information, and unvalidated input. These issues could allow attackers to access sensitive data, submit malicious input, bypass authentication, or gain control of the system.

At first, it took me some time to understand how to read the OWASP Dependency-Check report. Once I realized it showed which libraries needed to be updated or replaced, it became an invaluable tool.

Security layers were strengthened by adding input validation, role-based authorization to an endpoint, and secure communication through HTTPS/TLS.

To ensure the application was functional, I verified that both the application and Dependency-Check ran without errors. After refactoring the code, I ran Dependency-Check again and compared the new report to the original.

In the future, I will use the vulnerability assessment process flow diagram to guide manual code reviews, especially when checking for secure error handling and coding practices. OWASP Dependency-Check will also be an invaluable tool.

After this project, I could show future employers my vulnerability assessment, refactored code, and OWASP Dependency-Check reports. This demonstrates my ability to manually inspect code for security weaknesses, identify vulnerable dependencies, apply secure coding practices, and verify that an application still runs correctly after security improvements. I could also show the added layers of security, such as input validation and role-based authorization, to better protect client data and financial information.
