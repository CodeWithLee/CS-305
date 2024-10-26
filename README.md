•	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address? 

Artemis Financial is a consulting firm specializing in creating tailored financial plans for clients, covering areas such as savings, retirement, investments, and insurance. The company sought to modernize its software infrastructure, aiming to improve operational efficiency and strengthen its security posture. The primary goal was to address software security vulnerabilities, ensuring the protection of sensitive financial data and compliance with industry standards. My role was to conduct a thorough security assessment, identify potential vulnerabilities, and implement solutions to enhance the security of Artemis Financials software.

•	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being? 

I did well with identifying and prioritizing software security vulnerabilities, applying the most appropriate encryption algorithm to secure sensitive data. By leveraging the best algorithm cipher, I ensured that the software was protected against threats while maintaining performance. Secure coding practices are essential because they prevent unauthorized access, data breaches, and other cyber threats, which can have severe legal and financial consequences. For Artemis Financial, secure software helped protect customer data, maintain regulatory compliance, foster trust, and support long-term growth by reducing risks and potential disruptions.

•	Which part of the vulnerability assessment was challenging or helpful to you?

Updating outdated asset information, such as server configurations and database versions, proved to be particularly beneficial in providing a complete picture of the software's security posture. This ensured no vulnerabilities were overlooked due to outdated or incomplete records. A significant challenge was dealing with false positives and false negatives from the assessment tools. Sorting through these to determine which issues required attention involved careful analysis and testing, but this process helped refine my skills in distinguishing between critical vulnerabilities and less significant concerns.

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I enhanced the security layers by implementing cryptographic techniques, such as using the SHA-256 algorithm to add a checksum that generates a hash of a static data string. This technique ensured data integrity and minimized the risk of tampering. Additionally, I introduced a new route (/hash) to calculate and return the hash value alongside the original data securely. Moving forward, I would leverage automated vulnerability scanning tools (e.g., OWASP Dependency-Check) and manual code reviews to assess vulnerabilities. I would also evaluate mitigation techniques based on factors like threat severity, impact, and ease of implementation, prioritizing those that provide the most robust security with minimal disruption.

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure functionality and security, I updated the Maven Dependency Check to version 10.0.4, aligning the software with the latest security standards and best practices. After refactoring, I reviewed the code for potential security issues, ensuring no sensitive information was exposed. I enforced security protocols, such as converting HTTP requests to HTTPS to secure data transmission. Additionally, I compiled and tested the code locally, validating that the changes did not introduce new vulnerabilities or affect the application’s performance. I used security scanning tools and manual code reviews as part of a final check to verify that the updated software met security standards.

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Utilizing OWASP resources helped me stay updated on the latest security vulnerabilities and mitigations. In future projects, I would continue using tools like OWASP Dependency-Check to ensure all dependencies are secure. Additionally, generating self-signed certificates for testing and configuring secure protocols can be useful practices for securing data during development. The choice of cryptographic techniques, such as using Advanced Encryption Standard (AES) encryption algorithms, would be based on the specific security requirements of each software project.

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this project, I would demonstrate my ability to conduct a comprehensive vulnerability assessment, prioritize security issues, and implement effective mitigations. I would showcase how I applied encryption techniques, refactored code to enhance security, and ensured the software adhered to industry standards. Highlighting specific examples of identified vulnerabilities and the steps taken to resolve them would illustrate my skills in secure coding, problem-solving, and maintaining the balance between functionality and security.

