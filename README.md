# CS-305-Portfolio
CS 305 Portfolio Submission

## Project Overview

Artemis Financial is a financial services company that provides financial planning services, including savings, retirement, investments, and insurance. The purpose of this project was to improve the security of the company's software by identifying vulnerabilities, implementing secure communication, and applying secure coding practices.

### 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

My client was Artemis Financial, a company that provides financial planning services. The company wanted to improve the security of its software and protect information transmitted between users and its application. My task was to refactor the existing application, implement HTTPS, add SHA-256 checksum functionality, generate a certificate, and assess software vulnerabilities using security testing tools.

### 2. What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

I did well by examining the application's security requirements and applying appropriate security techniques. I implemented SHA-256 checksum generation using Java's standard cryptography library and configured HTTPS to protect communications between the browser and server. Secure coding is important because it helps prevent data exposure, unauthorized access, and other security problems. Strong software security also helps a company protect customer information, maintain trust, reduce the risk of costly incidents, and protect its reputation.

### 3. Which part of the vulnerability assessment was challenging or helpful to you?

Configuring HTTPS and working with certificates were challenging parts of the project. I learned how to generate a self-signed RSA certificate using Java Keytool and configure the application to use a PKCS12 keystore. Understanding the difference between hashing and encryption was also helpful. SHA-256 generates a digest that can help detect changes to data, while HTTPS/TLS protects information transmitted between the browser and server. These techniques serve different purposes and work together as layers of security.

### 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by implementing SHA-256 checksum generation, configuring HTTPS/TLS, generating an RSA certificate, and using secure coding practices. I also used OWASP Dependency-Check to assess third-party dependencies for known vulnerabilities. In future projects, I would continue using vulnerability scanners, code reviews, and functional testing. I would evaluate identified vulnerabilities based on their severity, exploitability, and potential impact before deciding which mitigation techniques to apply.

### 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I focused on building and running the application, checking the checksum functionality, and assessing dependencies with OWASP Dependency-Check. I used Java's standard `MessageDigest` API instead of creating a custom hashing algorithm. Functional testing helps verify that the application behaves as expected, while dependency scanning identifies known vulnerabilities in third-party libraries. Code reviews can also help identify problems that automated tools may miss. These checks are important because a successful build does not automatically mean an application is secure.

### 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used Java, Spring Boot, Eclipse IDE, Java Keytool, SHA-256, HTTPS/TLS, and OWASP Dependency-Check. I also applied secure coding practices, including using standard cryptographic libraries, selecting modern hashing algorithms, and separating checksum generation from application startup. These tools and practices will help me develop, test, and maintain secure software in future assignments and professional projects.

### 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show future employers my refactored Java code, the SHA-256 checksum implementation, the HTTPS configuration, the generated certificate, and the OWASP Dependency-Check report. I would also include screenshots demonstrating the application running and the checksum functionality working. These artifacts demonstrate my experience with Java programming, secure software development, cryptographic hashing, certificate generation, vulnerability assessment, and functional testing. This project provides an example of how I applied security concepts to an existing application and documented my work.

## Conclusion

This project helped me understand the importance of incorporating security throughout the software development process. By implementing checksum generation, configuring HTTPS, generating a certificate, and assessing third-party dependencies, I gained practical experience with secure software development. I will use these skills in future projects to help build applications that are functional, reliable, and secure.
