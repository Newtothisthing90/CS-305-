# CS 305 Software Security Portfolio
## README Reflection1
Artemis Financial was a financial services company that wanted to improve the security of its software application. The company needed stronger protection for sensitive client data and secure communication between systems. My role was to review the software, identify security weaknesses, and recommend or implement solutions that would improve the overall security of the application.

One area I did well in was identifying vulnerabilities through code review and automated scanning tools. I used OWASP Dependency-Check to locate outdated libraries and known risks in the project dependencies. Coding securely is important because it helps prevent data breaches, protects customer information, and reduces the chance of system downtime or financial loss. Strong software security adds value to a company by building customer trust, protecting its reputation, and lowering risk.

One challenging part of the vulnerability assessment was understanding how different vulnerabilities connect to real-world threats and deciding which ones should be addressed first. A helpful part of the process was learning how security tools can quickly identify risks that may not be obvious during manual review.

I increased layers of security by applying a defense-in-depth approach. I added HTTPS to encrypt communication, used SHA-256 checksum verification to support data integrity, reviewed dependencies for vulnerabilities, and improved configuration settings. In the future, I would continue using vulnerability scanners, code reviews, penetration testing, and risk-based analysis to determine the best mitigation techniques.

To make certain the software remained functional and secure, I tested the application after making changes and confirmed that all core features still worked correctly. I verified the checksum route functioned properly, confirmed secure browser connections through HTTPS, and reran security scans after refactoring to check for any newly introduced vulnerabilities.
Some of the most helpful resources and tools I used were Java, Spring Boot, Maven, OWASP Dependency-Check, secure coding practices, debugging methods, and software testing techniques. These tools and practices will continue to be useful in future coursework and professional tasks.

From this assignment, I would show future employers my vulnerability assessment report and secure software improvements. These artifacts demonstrate my ability to identify software risks, apply practical security fixes, test functionality after changes, and use professional tools to strengthen application security.
