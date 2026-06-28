# cs-305-project-one
Secure REST API vulnerability assessment and refactoring project using OWASP Dependency-Check, input validation, and role-based authorization.

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for customers. It sought to protect client data and financial information by securing its RESTful web API through manual code review and static testing with OWASP Dependency-Check.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Manual code inspection revealed several vulnerabilities that needed to be fixed, including stack traces printed to the console/logs, hardcoded sensitive information, and unvalidated input. These issues could allow attackers to access sensitive data, submit malicious input, bypass authentication, or gain control of the system.

# Which part of the vulnerability assessment was challenging or helpful to you?
At first, it took me some time to understand how to read the OWASP Dependency-Check report. Once I realized it showed which libraries needed to be updated or replaced, it became an invaluable tool.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Security layers were strengthened by adding input validation, role-based authorization to an endpoint, and secure communication through HTTPS/TLS.

#How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure the application was functional, I verified that both the application and Dependency-Check ran without errors. After refactoring the code, I ran Dependency-Check again and compared the new report to the original.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
In the future, I will use the vulnerability assessment process flow diagram to guide manual code reviews, especially when checking for secure error handling and coding practices. OWASP Dependency-Check will also be an invaluable tool.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
After this project, I could show future employers my vulnerability assessment, refactored code, and OWASP Dependency-Check reports. This demonstrates my ability to manually inspect code for security weaknesses, identify vulnerable dependencies, apply secure coding practices, and verify that an application still runs correctly after security improvements. I could also show the added layers of security, such as input validation and role-based authorization, to better protect client data and financial information.
